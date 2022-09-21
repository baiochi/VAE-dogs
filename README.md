# VAE-dogs
Desafio Técnico Hand Talk

*“Qual é o link entre os Autoencoders e a geração de conteúdo?”. De fato, uma vez que o Autoencoder foi treinado, temos um codificador e um decodificador, mas ainda não há uma maneira real de produzir qualquer novo conteúdo. À primeira vista, poderíamos ficar tentados a pensar que, se o espaço latente for regular o suficiente (bem “organizado” pelo codificador durante o processo de treinamento), poderíamos pegar um ponto aleatoriamente nesse espaço latente e decodificá-lo para obter um novo conteúdo. O decodificador agiria mais ou menos como o gerador de uma Rede Adversária Generativa ."*

FONTE: 

[Capítulo 60 - Variational Autoencoders (VAEs) - Definição, Redução de Dimensionalidade, Espaço Latente e Regularização - Deep Learning Book](https://www.deeplearningbook.com.br/variational-autoencoders-vaes-definicao-reducao-de-dimensionalidade-espaco-latente-e-regularizacao/)

Os Autoencoders Variocionais (Variational Auto-Encoders ou VAEs) fazem parte do estado da arte tanto quando se fala de redução de dimensionalidade em problemas utilizando seu *encoder* quanto na geração de novos exemplos utilizando o *decoder.*

Podemos encontrar uma utilziação classica da arquitetura VAE na representação de imagens dos digitos obtidos no *Mninst dataset.* 

Tendo essas informações e exemplos na suas mãos, um cientista de dados é capaz de criar e utilizar as VAEs em variados datasets para variados fins. Prezamos muito, além do impeto de aprender e adentrar em novos caminhos, pela criatividade dos nossos Hand Talkers.

Sua missão, se desejar aceitar, será a utilização de VAEs em imagens cachorros de diferentes raças, e tentar gerar raças novas com a missigenação das antigas, usando o seguinte dataset:

[Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification/data)

Será que você conseguiria descobrir que raças combinadas dão origem ao nosso patrimônio nacional, viralata caramelo?

![caramelo](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/71e3921f-d944-4d6b-9aed-36da867f52ea/Untitled.png)

Ou será que você descobre que raça é o querido mascote do nosso time de IA, o Pythinho?

![pythinho](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dbbecead-d571-4726-b11f-3360f440e52f/Untitled.png)

São essas e outras perguntas que você talvez você consiga responder com o sistema que você gerar, use muito python, tensorflow+keras ou pytorch e ☕ para vencer esse desafio. E ai, VAE topar esse desafio? 😄  
