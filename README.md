# ProjetoBancoJDBC
Atualização  do Projeto [Banco Fuctura](https://github.com/Edivaldo16/BancoFuctura/tree/main). Na versão anterior todos os dados do cliente eram armazenados em `ArrayList`, ou seja, quando se encerrava o console da IDE todos os dados armazenados eram apagados. Visando solucionar esse problema e aplicando os conhecimentos do curso de Java 02, resolvi atualizar o projeto implementando-o em JDBC, em que os dados do cliente ficam armazenados em 4 tabelas (`Conta Corrente`, `Conta Poupança`, `Endereço` e `Pessoa`) no DBeaver. A comunicação entre a IDE Eclipse e o DBeaver se dá através do My Sql. Clique [aqui](https://github.com/Edivaldo16/ProjetoBancoJDBC/blob/main/Projeto/ProjetoJDBC/ProjetoBancoJDBC.zip) para visualizar o projeto.

## Tabelas
### 1. Conta Corrente
![Tabelas](https://github.com/Edivaldo16/ProjetoBancoJDBC/blob/main/Projeto/Fotos/contacorrente.png)
### 2. Conta Poupança
![Tabelas](https://github.com/Edivaldo16/ProjetoBancoJDBC/blob/main/Projeto/Fotos/contapoupanca.png)
### 3. Endereço
![Tabelas](https://github.com/Edivaldo16/ProjetoBancoJDBC/blob/main/Projeto/Fotos/endereco.png)
### 4. Pessoa
![Tabelas](https://github.com/Edivaldo16/ProjetoBancoJDBC/blob/main/Projeto/Fotos/Pessoa.png)

## Implementações Futuras

* Criar um código que bloqueia a conta do cliente caso seja necessário;
* Implementar o projeto usando JPA com Hibernate;
* Implementar o projeto usando Spring Boot.

Qualquel feedback é bem vindo. 
