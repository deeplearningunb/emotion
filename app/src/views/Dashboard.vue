<template>
  <div class="dashboard">
    <h1>
    Resultados de como os usuários estão se sentido em tempo real.</h1>
    <div>
      <template v-for="(emotion, index) in emotions">
        <div :key="index">
          <strong>{{index}}</strong> clients: {{ emotion }}
        </div>
      </template>
    </div>
  </div>
</template>

<script>
export default {
  name: "Dashboard",
  data: function(){
    return {
      emotions: {
        angry: 0,
        neutral: 0,
        happy: 0
      },
      pusher_obj: null,
      e_channel: null,
    }
  },
  mounted: function(){
    this.init();
  },
  methods: {
    init (){
      this.pusher_obj = new Pusher(process.env.PUSHER_APPKEY,{
          cluster: process.env.PUSHER_APPCLUSTER,
          encrypted: true
      });
      this.e_channel = this.pusher_obj.subscribe('emotion_channel');
      let self = this;
      this.e_channel.bind('new_emotion', function(data) {
        self.emotions[`${data.emotion}`] += 1;
      });
    },
  },
}
</script>

