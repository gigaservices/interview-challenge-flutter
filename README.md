# Random User API

### O projeto será uma aplicação em Flutter composta pelos itens abaixo: 

#### 1. Consultar uma lista de usuários da API https://randomuser.me/api/, salvando o resultado no banco de dados local.

- Use os seguintes parâmetros na consulta:

  - format=json
  - page=
  - results=15
  - inc=gender,name,email,picture
  - nat=br

- As imagens da API deverão ser armazenadas localmente.
- Exibir na listagem da consulta a imagem do usuário, nome e email.
- Utilizar paginação de 15 registros por vez com sistema de scroll infinito ou botão para carregar mais.
- Implementar filtro de usuários por sexo (gender).

#### 2. Exibir detalhes do usuário

- Exibir a imagem e todas as informações da consulta do usuário ao clicar em um usuário da listagem.
 
### Regras

- Utilizar framework Flutter.
- Não é necessário exigir autenticação dos usuários que utilizarão a aplicação.
 
### Extras (serão bem avaliados) 

- Construir UI e UX seguindo os padrões do Material Design [https://material.io/design].
- Salvar os dados da API no banco de dados local servindo como cache.
- Bom tratamento de erros ao consultar API externa.
- Paginar resultados usando método do scroll infinito.
- Escolha de libs populares e estáveis para auxiliar no desenvolvimento.
- Aplicar técnicas mais avançadas como injeção de dependência e design patterns.
- Testes unitários.

### Pontos que serão avaliados: 

- Cumprimento dos objetivos propostos.
- Preocupação com organização, padronização, modularização e qualidade do código.
- Aplicação da lógica de programação e otimização de código.
- Tempo para conclusão do projeto.
