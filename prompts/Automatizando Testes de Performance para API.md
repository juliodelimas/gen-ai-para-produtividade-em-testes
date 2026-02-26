# Automatizando Testes de Performance para API.md

## Objetivo
Implementar a automação de testes de performance para API para o método POST /checkout.

## Contexto
- A especificação da API para o método POST /checkout está no arquivo swagger.yaml.
- Existem testes funcionais automatizados para o método POST /checkout na pasta test escritos com Javascript, Mocha e Supertest que podem ser utilizados como referência
- O arquivo README.md já contém informações sobre os usuários e produtos cadastrados na API.

## Regras
- Crie casos de teste de performance para o fluxo principal.
- Utilize Javascript e K6 (K6 já está instalado).
- Os testes devem ser colocados em uma pasta com o mesmo nome do endpoint, dentro da pasta test/k6.
- Utilizar fixtures e isolar os dados de teste.
- Criar uma função auxiliar para realizar o login e obter o token JWT.
