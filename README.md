# Lab02 - Integração Contínua com GitHub Actions - Exercício 2

---

Este repositório contém a implementação de **Integração Contínua (CI)** utilizando **GitHub Actions**. O objetivo deste exercício foi configurar dois workflows para automatizar o processo de **build**, **teste** e **deploy** do código. A primeira parte envolveu a configuração de um workflow simples e a segunda parte a adição de um workflow mais avançado, com múltiplas etapas encadeadas.

## Objetivo

O principal objetivo do exercício 2 foi criar e configurar dois workflows no GitHub Actions:

1. **Workflow V1**:
   - Configuração de um workflow simples para automatizar o processo de **checkout do código**, **instalação de dependências** e **execução de um script Node.js**.
   
2. **Workflow V2**:
   - Configuração de um workflow mais complexo com etapas **encadeadas**: **Lint**, **Testes**, **Build** e **Deploy**. O Workflow V2 foi configurado para garantir que cada etapa só fosse executada se a anterior fosse bem-sucedida.

## Estrutura do Projeto

- **.github/workflows/build.yml**: Arquivo de configuração do GitHub Actions com o workflow **Build V1**.
- **.github/workflows/build02.yml**: Arquivo de configuração com o **Build V2**, que inclui as etapas de **Lint**, **Testes**, **Build** e **Deploy**.
- **package.json**: Arquivo que define as dependências do projeto, incluindo o pacote `moment`.
- **app.js**: Script simples que exibe a data atual utilizando o pacote `moment`.
- **.gitignore**: Arquivo que configura o que o Git deve ignorar (como o diretório `node_modules`).
- **README.md**: Este arquivo de documentação.

## Conclusão

Concluí o exercício com sucesso, configurando dois workflows de Integração Contínua no GitHub Actions. O primeiro workflow (Build V1) foi simples e automatizou as etapas de checkout do código, instalação de dependências e execução do script Node.js. Já o segundo workflow (Build V2) foi mais avançado, incorporando etapas encadeadas de Lint, Testes, Build e Deploy, o que me permitiu entender como as etapas podem ser organizadas e dependentes entre si.

Com isso, pude perceber os benefícios da automação de processos de verificação, teste e deploy. Agora, sempre que há alterações no código, o GitHub Actions garante que o código seja validado, testado e preparado para produção de forma automatizada, sem intervenção manual. Essa experiência foi fundamental para entender como a Integração Contínua e a Entrega Contínua (CD) podem otimizar o fluxo de trabalho e aumentar a confiabilidade do software.

---

### Discente: Alicia Caldeira
### Curso: Web Academy - UFAM
