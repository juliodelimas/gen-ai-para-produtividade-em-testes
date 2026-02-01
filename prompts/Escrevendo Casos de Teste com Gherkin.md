# Escrevendo Casos de Teste com Gherkin

## Objetivo
Escreva os casos de teste de cadastro com sucesso e com falha para o formulário de cadastro de pessoas.

## Contexto
- Os casos de teste serão escritos com Gherkin, com template padrão, contendo Dado (pre-condições), Quando (ações) e Então (pós condições).
- O código HTML do formulário está em anexo

## Regras
- Descreva os casos de teste levando em consideração os campos do formulário
- Avalie o código para entender quais mensagens podem ser retornadas em caso de sucesso ou falha

## Exemplo
Cenário: Cadastro de pessoa realizado com sucesso
Dado que possuo todos os dados da pessoa
Quando acesso o site
E clico no campo Nome
...
E cllico em Submeter
Então a mensagem "Submetido com sucesso (mock)" será exibida
E o registro será apresentado na área Mock de submissões (histórico local)"

## Formato
Cenários em Gherkin.
