# Desafio Nginx com Node.js

Desafio apresentado no curso Full Cycle (módulo Docker).

O desafio consiste em apresentar uma mensagem na tela utilizando nginx com node.js.

Quando uma chamada for feita a aplicação, esta deverá salvar um registro no bando de dados (MySQL).
Em seguida, a página deverá apresentar a mensagem ```Full Cycle Rocks!```, logo abaixo uma lista com os registros do banco.

Nota: A página deverá ser construída em node mas será acessada pelo nginx através de um proxy reverso!

---

### Para rodar a aplicação utilize o docker-compose.

```
docker-compose up -d
```

---

#### Acesse a aplica em: [http://localhost:8080/](http://localhost:8080/)