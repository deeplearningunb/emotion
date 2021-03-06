### Emotion

Este projeto consiste-se na detecção de emoções a partir da webcam, é util caso seja utilizado como complemento de algum sistema, possibilitando a detecção da emoção de um usuário acerca de uma determinada atualização no software, ou satisfação na utilização de alguma funcionalidade contida no sistema.
  
### O que é Deep Learning?

É uma técnica muito específica de Machine Learning, e consequentemente de Inteligência artificial. É uma maneira de implementar a técnica específica, que usa as chamadas redes neurais artificiais, correspondentes a uma classe de algoritmos de machine learning. Sendo assim, temos que **Deep Learning**, é uma técnica de Machine Learning, baseada em redes neurais artificiais.

### O que é uma Rede Neural Convolucional?

No contexto de inteligência artificial e aprendizagem de máquina, uma Rede Neural Convolucional (Do inglês - ***<i>Convolutional Neural Network***</i>) é uma classe de rede neural artificial do tipo ***<i>feed-forward***</i>, que vem sendo aplicada com sucesso no processamento e análise de imagens digitais. Neste projeto fora utilizado o ***MobileNet***. Mobilenet é uma simplificação de redes neurais para possibilitar o seu uso em aplicações web. Eles foram inicialmente projetados para economizar recursos computacionais. O nível de precisão de uma MobileNet é menor que as redes neurais tradicionais, para agilizar o tempo de processamento e economizar recursos.
  
### O que é o Tensorflow.JS?

TensorFlow é uma biblioteca de código aberto para aprendizado de máquina aplicável a uma ampla variedade de tarefas. É um sistema para criação e treinamento de redes neurais para detectar e decifrar padrões e correlações, análogo, porém não idêntico à forma como humanos aprendem e raciocinam. Ele é usado tanto para a pesquisa quanto produção no Google. O TensorFlow foi desenvolvido para ter suporte de várias linguagens. A linguagem suportada e utilizada neste projeto foi o JavaScript, porém o melhor suporte obtido pela biblioteca é na linguagem Python.

### Como testar o projeto?

Entre na pasta app e execute o comando:

> docker-compse up --build

Em outro terminal, entre na pasta server e execute o mesmo comando:

> docker-compse up --build

Acesse a porta 8080:

> http://localhost:8080

Faça o treinamento selecioando as opções: Angry, Neutral ou Happy. Em seguida vá para o modo de teste, clique no botão 'Treine o modelo' e o resultado aparecerá logo abaixo, existe um dashboard com a contagem dos resultados.

Para acessar o dashboard acesse com a rota:

> http://localhost:8080/dashboard

### Próximos passos

A equipe traçou os seguintes objetivos de evolução para o projeto:

- **Lançar v0.2** - No atual momento, para realizar um treinamento, as imagens devem ser tiradas pelo próprio usuário. A ideia é que no futuro, assim que o programa for inicializado, ele utilize um banco de imagens para realizar um treinamento automático.

- **Lançar v0.3** - O passo seguinte seria realizar o deploy da aplicação, para que seja possível os usuários contribuirem com o treinamento, tornando nossa base imagens maior e a classificação cada vez melhor, além de facilitar o acesso dos usuários a aplicação.

Caso queira ajudar na evolução do projeto, confira o tópico **Quero ajudar! Como contribuir?** 

### Conheça nossa equipe

| Membro | E-mail | Github |Matricula|
|-------------------------------|--------------------------|----------------------------------|------------|
| Lucas Siqueira	| lucassiqzro@gmail.com | [lucassiqz](https://github.com/lucassiqz) | 15/0137567|
| Lucas Lermen	| lucas.arthur.lermen@gmail.com | [lucasLermen](https://github.com/lucasLermen) |16/0012961|
| Lucas Macedo	| lpalucas.10@gmail.com | [lukassxp](https://github.com/lukassxp) |15/0137397|
| Matheus Rodrigues	| matheus.1nascimento58@gmail.com | [matheus-rn](https://github.com/matheus-rn) |16/0015294|
| Vitor Leal	| vitor_leal2201@hotmail.com | [vitorl-s](https://github.com/vitorl-s) |16/0148375|

### Quero ajudar! Como contribuir?
<p align="justify"> Sua ajuda é muito bem vinda! O guia com todos os passos para contribuir ao Emotion se encontra <a href="https://github.com/deeplearningunb/emotion/blob/master/CONTRIBUTING.md">aqui</a> e não esqueça de seguir nosso código de conduta, para conferir basta clicar <a href="https://github.com/deeplearningunb/emotion/blob/master/CODE_OF_CONDUCT.md">aqui</a>.</p>

### Licença
Esse projeto utiliza a licença MIT. Para mais informações [clique aqui](https://github.com/deeplearningunb/emotion/blob/master/LICENSE)

### Referências

https://en.wikipedia.org/wiki/Convolutional_neural_network <br>
https://en.wikipedia.org/wiki/TensorFlow <br>
https://www.sas.com/pt_br/insights/analytics/deep-learning.html <br>
https://blog.fellyph.com.br/javascript/o-que-e-mobilenet/
