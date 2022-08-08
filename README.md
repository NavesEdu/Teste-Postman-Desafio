# Postman Desafio

- [Sobre](#-sobre)
- [Como executar](#-como-executar)


## 💻 Sobre

Este é um projeto usando Postman para criação de testes da API pública https://serverest.dev/, nesse projeto são testadas as funcionaldiades de realizar login na aplicação com / sem sucesso, utilizando o browser google chrome:
<br/>

## 🚀 Como executar

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina a seguinte ferramenta:

* [Postman](https://www.postman.com/downloads/)

### Clonando repositório

Para clonar o repositório em algum lugar na sua máquina, basta utilizar o comando abaixo:
```bash
$ git clone https://github.com/NavesEdu/Teste-Postman-Desafio
```
### Primeiro modo:
## Iniciando a aplicação

1. Abra o Postman
2. Selecione o menu *File -> Import*
3. Selecione a aba *File*
4. Clique no botão *Upload Files*
5. Navegue até o diretório onde você salvou o arquivo e selecione os arquivos `usuarios-Serverest-collection.json` e o arquivo `usuarios.postman_env`
6. Clique no botão *Import*

## Fazendo os testes

* Environment criado dentro do Postman com a URL da API:
</p>
<p aligng="center">
  <img src="to_ReadME/env.png">
</p>

* Teste da requisição GET, que retorna todos usuários já cadastrados:
<p aligng="center">
  <img src="to_ReadME/postman1.png">
</p>

* Teste da requisição POST, que cadastra um usuário:
<p aligng="center">
  <img src="to_ReadME/postman2.png">
</p>

* Teste da requisição DEL, que deleta um usuário, no caso do exemplo, nenhum registro foi deletado pois foi usado um ID qualquer:
<p aligng="center">
  <img src="to_ReadME/postman3.png">
</p>

* Teste da requisição PUT, que atualiza o registro de um usuário, no caso do exemplo, foi usado o ID do usuário que foi cadastrado no exemplo da requisição POST:
<p aligng="center">
  <img src="to_ReadME/postman4.png">
</p>

### Segundo modo:
Vendo os testes através de um CI criado com o GitHub Actions, utilizando o newman:
* 
