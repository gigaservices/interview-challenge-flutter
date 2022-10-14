# Random User API

### O projeto será uma aplicação em Flutter composta pelos itens abaixo: 

#### 1. Consultar uma lista de usuários da API https://randomuser.me/api/, salvando o resultado no banco de dados local.

- Use os seguintes parâmetros na consulta:

  - format=json
  - page=*numero_da_pagina*
  - results=15
  - inc=gender,name,email,picture
  - nat=br

- Exibir na listagem da consulta a imagem do usuário, nome e email.
- Implementar paginação de 20 registros por vez com botão para carregar mais ou sistema de scroll infinito.
- Implementar filtro de usuários por sexo (gender).

#### 2. Exibir detalhes do usuário

- Exibir a imagem e todas as informações da consulta do usuário ao clicar em um usuário da listagem.
 
### Regras

- O código precisa ser escrito em inglês.
- Utilizar a versão mais recente do Flutter.
- Construir UI (telas e componentes) da sua maneira seguindo os padrões do Material Design [https://material.io/design].
- Buscar aplicar uma arquitetura limpa, desacoplável e escalável de acordo com seu conhecimento.
- Escolher e aplicar algum padrão de gerenciamento de estado que conheça bem como MobX (a que utilizamos), Provider, BloC, GetX, etc.
 
### Extras opcionais (serão bem avaliados) 

- Salvar os dados da API no banco de dados local servindo como cache.
- Fazer o correto tratamento de erros ao consultar a API de acordo com seu tipo (Ex.: tratar erro de conexão, dados inválidos, etc).
- Escolher bibliotecas populares e estáveis para auxiliar no desenvolvimento.
- Ter domínio e aplicar técnicas mais avançadas como injeção de dependência e utilização de algum Design Pattern como Repository Pattern.
- Desenvolver testes unitários e de widgets.

### Pontos que serão avaliados: 

- Cumprimento dos objetivos propostos.
- Preocupação com organização, padronização, modularização e qualidade do código (Clean Code).
- Desenvolvimento de código bem modularizado e com separação de responsabilidades.
- Construção da interface utilizando corretamente as recomendações do Material Design. 

### Instruções

- *Não é necessário disponibilizar a versão web e nem gerar um APK.*
- *Compartilhe o link do seu repositório ao finalizar o projeto.*

### Perguntas

Ao compartilhar o link do projeto finalizado, pedimos que responda mais 3 perguntas adicionais a seguir:

1) Quais padrões de gerenciamento de estados já utilizou em seus projetos ou que tem bons conhecimentos?

2) Tem conhecimentos de SOLID e arquitetura limpa? Se sim, já utilizou em algum projeto?

3) Poderia listar e compartilhar projetos em Flutter já realizados?
