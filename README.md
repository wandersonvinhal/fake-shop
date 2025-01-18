# Desafio Devops & Cloud

Este repositório contém um exemplo de pipeline CI/CD integrado com Kubernetes e Grafana. A estrutura do projeto é descrita abaixo:

## Estrutura do Projeto

- **.github/workflows/main.yaml**: Workflow do GitHub Actions para configurar o pipeline CI/CD.
- **src/**: Diretório onde fica o código-fonte da aplicação.
- **deployment.yaml**: Arquivo de configuração para o deploy no Kubernetes.
- **grafana/dashboard-flask.png**: Captura de tela do dashboard configurado no Grafana.

## Pipeline CI/CD (GitHub Actions)

O pipeline realiza as seguintes etapas:
1. **Build**: Compila a aplicação.
2. **Docker Build & Push**: Constrói e envia a imagem Docker para o Dcoker Hub.
2. **Deploy no Kubernetes**: Faz o deploy da aplicação no cluster Kubernetes na AWS.




