# Exemplo de Aula Prática: CI/CD

## Descrição para Mesclar

Este repositório contém um exemplo de implementação de **Integração Contínua (CI)** e **Entrega Contínua (CD)**, utilizado para demonstrar como automatizar o processo de build, testes e deploy de uma aplicação. O objetivo desta aula prática é fornecer um entendimento básico sobre como essas práticas ajudam no desenvolvimento de software moderno, melhorando a qualidade e a velocidade de entrega.

## Tecnologias Utilizadas

- **GitHub Actions**: Para automação do processo de integração e deploy contínuo.
- **Docker**: Para containerização da aplicação.
- **Node.js**: Como aplicação de exemplo (mas o conceito pode ser adaptado para outras linguagens).
- **Jest**: Para testes automatizados.
- **Heroku**: Como plataforma de deploy.

## Como Funciona

1. **Integração Contínua (CI)**:
   - Cada commit no repositório dispara um workflow no GitHub Actions.
   - O processo inclui a instalação das dependências, execução dos testes automatizados e criação de uma imagem Docker.
   
2. **Entrega Contínua (CD)**:
   - Após a execução bem-sucedida do pipeline de CI, o código é automaticamente implantado em um ambiente de produção no Heroku.
   - Isso garante que qualquer alteração no código seja rapidamente disponibilizada aos usuários sem intervenção manual.

## Passos para Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/exemplo-ci-cd.git
   cd exemplo-ci-cd
