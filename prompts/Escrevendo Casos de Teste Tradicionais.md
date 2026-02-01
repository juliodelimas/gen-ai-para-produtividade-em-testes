# Escrevendo Casos de Teste Tradicionais

## Objetivo
Escreva os casos de teste de cadastro com sucesso e com falha para o formulário de cadastro de pessoas.

## Contexto
- Os casos de teste serão escritos inspirados no ISO-29119-3, com template padrão, contendo ID, título, pre-condições, ações com resultado esperado para cada ação e pós condições da execução.
- O código HTML do formulário está em anexo
- A única validação contida no formulário é a de que todos os campos devem ser preenchidos com sucesso

## Regras
- Descreva os casos de teste levando em conideração os campos do formulário
- Avalie o código para entender quais mensagens podem ser retornadas em caso de sucesso ou falha

## Exemplo
id=987, titulo="Cadastro de pessoa realizado com sucesso", pre-condições="Possuir todos os dados da pessoa", ações com resultado esperado="Passo 1: Acessar o site, Resultado esperado do Passo 1: Site do cadastro de pessoas será exibido; Passo 2: Clicar no campo Nome, Resultado esperado do Passo 2: Campo receberá o cursor e terá uma borda roxa; ...; Passo 9: Clicar em Submeter, Resultado esperado do passo 9: Mensagem Submetido com sucesso (mock).
 será exibida", pós-condições="Registro será apresentado na área Mock de submissões (histórico local)".

## Formato
Lista de casos de teste.
