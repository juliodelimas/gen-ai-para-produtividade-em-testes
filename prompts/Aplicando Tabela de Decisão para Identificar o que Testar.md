# Aplicando Tabela de Decisão para Identificar o que Testar

## Objetivo
Utilize a Tabela de Decisão para identificar quais testes podem ser executados para avaliar a User Story em anexo. 

## Contexto
- Técnica de teste: uma forma estruturada de identificar o quais testes podem ser realizados em uma determinada parte do software.
- Técnicas de teste baseadas na especificação: Técnica de teste que é baseada em requisitos e documentação de um software.
- Partição de quivalência: Técnica baseada na especificação que analisa um trecho da regra de negócio, identifica as entradas do usuário, depois identifica quais são as faixas de valores (partições) que disparam regras específicas e seleciona um valor que represente cada uma das partições.
- Tabela de decisão: Técnica baseada na especificação que usa os resultados da partição de equivalência, para combinar todas as entradas e determinar quais as sídas para cada entrada com base no requisito. Um requisito pode ter várias tabelas de decisão, o que define a quantidade de tabelas é o quanto uma entrada é dependente da outra. Cada combinação de entradas e saídas forma um caso de teste.  Combinações sem saídas definidas tornam-se perguntas para o Product Owner, para esclarecer o possível gap na documentação.

## Regras
- Antes de construir a tabela de decisão, analise a dorreção de dependência entre as entradas identificadas
- Não utilize outras técnicas de teste (ex. Análie do valor limite)
- Não utilize testes exploratórios
- Não suponha ou crie hipóteses

## Exemplo
- Regras correlacionadas: 1) A transferência só pode ocorrer entre contas pertencentes ao mesmo cliente e 2) Contas externas ou de terceiros devem ser rejeitadas.
- Entradas: Dono da Conta e Tipo da Conta
- Partições de equivalência: Origem da Transferência (Dono da Conta e Outro Cliente), Destino da Transferência (Dono da Conta e Outro Cliente) e Tipo da Conta (Interna, Externa ou Terceiro)
- Quantidade de Combinações: Origem da Transferência (2) * Destino da Transferência (2) * Tipo da Conta (3) = 12 combinações
- Primeiro caso de teste da Tabela de Decisão: Origem da Transferência = Dono da Conta, Destino da Transferência = Dono da Conta, Tipo da Conta = Interna, Resultado Esperado = Não é permitido transferir para a mesma conta

## Formato
- Descrever as informações definidas para 1) Regras Correlacionadas, 2) Entradas, 3) Partições de Equivalência, 4) Quantidade de Combinações e 5) Tabela e casos de teste com as colunas (Entradas, Partições de cada entrada, CT1, CT2, ...) e as linhas de interseção de CT mostram um X para a partição selecionada.
