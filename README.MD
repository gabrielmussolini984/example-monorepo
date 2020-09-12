# Monorepo Example
> Um template de aplicação com microserviços utilizando também react e nodejs, monorepo feito utilizando yarn workspaces

## Exemplo de uso
_Foi feito um deploy no Google Cloud, e pode ser acessado pelo link a seguir:  [App][app]._ 

## Configuração para Desenvolvimento

Clone o repositório e depois instale as depêndencias:
```sh
yarn
```
Para rodar testes em todos packages:
```sh
yarn teste
```
Para instalar uma depêndencia "global":
```sh
yarn add nome-dependencia -W
```
Para rodar comandos dentro de algum package utilize:
```sh
yarn workspace @nome-projeto/nome-package start
```
Sempre tente utilizar depêndencias na mesma versão entre projetos, para ter o melhor aproveito de um monorepo.

## Meta

Gabriel Mussolini – gabrielmussolini@hotmail.com

[GITHUB](https://github.com/gabrielmussolini984)




