# Desafio Devops & Cloud

Este repositório contém um exemplo de pipeline CI/CD integrado com Kubernetes e Grafana. A estrutura do projeto é descrita abaixo:

## Estrutura do Projeto

/ ├── README.md # Documentação do projeto ├── .github/ │ └── workflows/ │ └── main.yaml # Pipeline CI/CD configurado para o GitHub Actions ├── src/ # Código-fonte do projeto ├── deployment.yaml # Arquivo de deployment para Kubernetes └── grafana/ └── dashboard.png # Captura de tela do dashboard do Grafana

## Pipeline CI/CD (GitHub Actions)

O pipeline realiza as seguintes etapas:
1. **Build**: Compila a aplicação.
2. **Docker Build & Push**: Constrói e envia a imagem Docker para o Dcoker Hub.
2. **Deploy no Kubernetes**: Faz o deploy da aplicação no cluster Kubernetes na AWS.




