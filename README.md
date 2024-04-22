# BootCamp01 QaulitersClub 
Teste de API Rest do manual CI/CD  

## O que é 
Este Repositório foi criado para o bootcamp de testes de API Rest.

## Tecnologias utilizadas
- Postman
- Node version v21.7.3
- newman v6.1.2
- newman-reporter-html


## Documentação
- Analise técnica: Analise/
- Doc da API: [consulte Swagger](https://serverest.dev)


## Como instalar o ambiente 
- Primeiro: instale o node no seu computador: [Baixe aqui](https://nodejs.org/en/download/current)
- Segundo: realize a instalação do newman de forma global: [Baixe aqui a dependência](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: Realize a instalação da dependência dos relatórios (opcional): [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```

## Como rodar os testes

### Pelo Postman web ou desktop
- Import a collection e o enviroment
- Execute os testes de forma manual ou automatizada

### Pelo newman
- Abra o consele de sua preferência
- Execute a seguinte linha de comando para rodar os testes
```
newman run ServeRest.postman_collection.json -e ServeRest_env.postman_environment.json -r cli
```
- Execute a seguinte linha de comando para rodar os testes com relatório 
```
newman run ServeRest.postman_collection.json -e ServeRest_env.postman_environment.json -r cli,html
```

## Entre em contato
[Linkedin](https://www.linkedin.com/in/iago-freire-178a7b297/)
