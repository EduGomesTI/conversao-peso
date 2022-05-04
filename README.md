# conversao-peso

Desafio Docker

Passos para criar o container da aplicação em .Net:

* Criar o arquivo dockerfile utilizando as imagemns sdk e runtime do .Net como base.

* Rodar o comando **"docker build -t _\<imagem:versao\>_ ."** para criar a imagem onde:

1. _\<imagem:versao\>_ = É o nome da imagem e sua versão seguindo a convensão id_docker/nome:v1.

* Rodar o comando **"docker container run -d -p 8080:80 --name _\<container\>_ _\<imagem:versao\>_"** onde:

1. _\<container\>_ = nome do container.

2. _\<imagem:versao\>_ = O nome da imagem criada e sua versão.

* Acessar o aplicativo pelo browser no camlinho localhost:8080