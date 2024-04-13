# api

Esta pasta cont�m os projetos que constituem a API.

Segue a organiza��o das pastas:

## /src

Cont�m os projetos que estruturam as camadas da aplica��o:

- `Api`: camada inicial com endpoints que recebem e retornam dados requisitados;
- `Application`: camada que processa as requisi��es e realiza as chamadas ao `Domain`;
- `Domain`: camada que cont�m as principais regras de neg�cio; e
- `Infrastructure`: camada que realiza o acesso ao banco de dados.

## /tests

Cont�m o projeto `UnitTests` -- o projeto de testes unit�rios da API.