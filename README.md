## Desafio Nginx com Node.js

Desafio apresentado no curso Full Cycle (módulo Docker).

O desafio consiste em apresentar uma mensagem na tela utilizando nginx com node.js.

Quando uma chamada for feita a aplicação, esta deverá salvar um registro no bando de dados (MySQL). Em seguida, a página deverá apresentar a mensagem `<h1>Full Cycle Rocks</h1>!`, logo abaixo uma lista com os registros do banco.

Nota: A página deverá ser construída em node mas será acessada pelo nginx através de um proxy reverso!


### Para rodar a aplicação utilize o docker-compose.


`docker-compose up -d`



### Para acessar, digite o seguinte endereço no navegador:

http://localhost:8080/
