# Criando Variações de Dados de Teste

## Objetivo
Crie variações de dados de teste para o cadastro de pessoas no sistema.

## Contexto
Pessoas podem ter nome, sobrenome, sexo, email, telefone e endereço. Abaixo estão as definições de cada um desses atributos.
- Nome é apenas o primeiro nome (opde ser composto, como Ana Maria), de pessoas brasileiras, até 55 caracteres.
- Sobrenome pode ser um conjunto de mais nomes, brasileiros, até 200 caracteres.
- Sexo pode ser masculino, feminino, não informado.
- Email é geralmente uma junção de primeiro nome e alguns dos sobrenomes com dominios de nomes de sites que fornecem email gratuito (ex. gmail, hotmail, etc.).
- Telefone possui o formato (99) 99999-9999 para celulares ou (99) 9999-9999 para telefone residencial ou comercial.
- Endereço abriga endereços brasileiros, com nome da rua, número da casa, bairro, cidade, estado e cep.

## Regras:
- Não crie dados de teste com emais duplicados.
- Crie apenas 50 dados de teste.

## Exemplo:
nome="Julio César", sobrenome="de Lima Costa", sexo="Masculino",  email="juliocesar.costa@gmail.com", telefone="(11) 99999-1122" e endereço="Rua das Oliveiras, 12, Bairro Dias Santos, Oliveirinhas, SP, 12345-543".

## Formato:
JSON
