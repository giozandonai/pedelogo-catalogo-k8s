# Projeto pedelogo-catalogo

*Sobre o projeto*
O projeto pedelogo-catalogo é uma aplicação escrita em C# e tem como objetivo ser uma aplicação de exemplo pra trabalhar com o uso de containers.
Neste repositório, estamos utilizando para o Desafio: **Kubernetes Fundamentos**.

### Observações do projeto
A infraestrutura é on Premise e utiliza o ingress Bare Metal para exposição da aplicação.
A aplicação é exposta usando a porta 80.

### Imagem
Local: **srv/Dockerfile**

Repositório: **Docker Hub - [giozandonai](https://hub.docker.com/u/giozandonai)**

**Criando a imagem sem o compose:** `$ docker build -t giozandonai/pedelogo-catalogo:v1.0.0 .`

## Acessando a aplicação KUBERNETES:
Acessar a pasta ./k8s:<br>
`kubectl apply -f . -R`<br>
`http://nome_dominio`<br>