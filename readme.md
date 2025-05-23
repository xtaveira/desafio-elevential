# Desafio Elevential

## Escopo
O seu cliente, Carvalho, é um catalogador de Pokemon. Ele precisa de um sistema para deixar mais fácil o cadastro de novas espécias que ele vem encontrando em suas pesquisas, de forma simples e rápida, através de um sistema web.
Carvalho já tem uma lista com 150 desses Pokemons, e o sistema deve vir com esses Pokemons pré-cadastrados.
[Esses dados podem ser encontrados aqui](./dados_iniciais.json)

Cada Pokemon terá as seguintes informações:
1. Código
2. Nome
3. Tipo
4. Tipo secundário
   1. Campo opcional

Cada tipo terá as seguintes informações:
1. Código
2. Nome


## Requisitos
1. Forma de cadastrar, listar, editar e deletar Pokemons, conforme a descrição do que precisa ser salvo em um Pokemon
2. Forma de cadastrar, listar, editar e deletar tipos
3. Criação dos Pokemons que Carvalho tem, dispnibilizaro [aqui](./dados_iniciais.json)
4. Listagem com filtros de nome e tipo
5. Repositório no github com o código
6. Descrição no readme do repositório, ensinando como rodar na máquina localmente o seu sistema

## Opcionais
1. Video mostrando o uso do sistema no Youtube, no readme do repositório
2. Hospedagem na internet
3. Containerização do sistema

## Stack

O desafio pode ser realizado com qualquer stack de preferência do participante.

Caso não tenha nenhuma em mente, recomendações possíveis são:
1. Python -> Django
2. Python -> Django + React
3. Node.js -> Mongo, Express, React("MERN")
4. C# -> DOTNET + React
5. Ruby -> Ruby on Rails

## Esboço do Banco de Dados
![img](Imagens/escopo_banco.png)

# Exemplo básico funcional
## [Um exemplo do minimo que é esperado pode ser encontrado aqui](https://desafio-pokedex.elevential.com/)