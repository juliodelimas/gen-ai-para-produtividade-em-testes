# Automatizando Testes de API Rest

## Objetivo
Implementar a automação de testes funcionais da API para o método POST /checkout.

## Contexto
- A especificação da API para o método POST /checkout está no arquivo swagger.yaml.
- As regras para o Checkout estão no ticket Jira ATD-12, sob o nome juliodelima.atlassian.net.
- O arquivo README.md já contém dados sobre usuários e produtos cadastrados.

## Regras
- Criar casos de teste para o fluxo principal de cada operação, utilizando apenas testes funcionais.
- Utilizar Javascript, Mocha, Supertest e Chai.
- Os testes devem ser colocados em uma pasta com o mesmo nome do endpoint, dentro da pasta test.
- Utilizar fixtures e isolar os dados de teste.
- Criar uma função auxiliar para realizar o login e obter o token JWT.
