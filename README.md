# Desafio Beedoo 🐝

## User Stories

### Funcionalidade: Cadastrar novo curso

**Como** usuário do Beedoo QA Challenge
**Quero** cadastrar um novo curso
**Para que** ele possa ser listado na página de cursos

| #   | REGRAS DE NEGÓCIO |
|-----|-------------------|
RN001 | Devem estar disponíveis os campos "Nome do Curso", "Descrição do Curso", "Instrutor", "URL da Imagem da Capa", "Data de Início", "Data de Fim", "Número de Vagas", e "Tipo de Curso", sendo todos eles obrigatórios.
RN002 | O campo "Data Início" deve possuir uma data igual ou posterior ao dia que esta sendo realizado o cadastro.
RN003 | O campo "Data Fim" deve possuir uma data igual ou posterior à "Data Início".
RN004 | O campo "Número de Vagas" deve ser um número inteiro positivo.
RN005 | O campo "Tipo do Curso" possuir apenas as opções "Presencial" e "Online".
RN006 | Caso o Tipo do Curso escolhido for "Presencial", o campo "Endereço" deverá ser exibido e é um campo obrigatório.
RN007 | Caso o Tipo do Curso escolhido for "Online", o campo "Link de Inscrição" deverá ser exibido e é um campo obrigatório.
RN008 | Ao cadastrar um novo curso, o usuário deve receber uma mensagem de confirmação de cadastro com sucesso, e ser redirecionado para a página de listagem de cursos.


**Critérios de Aceite:**

**Dado** que o usuário esta na na página de cadastro de cursos,
**Quando** ele preencher todos os campos obrigatórios corretamente,
**E** clicar em "Salvar",
**Então** o novo curso deve ser criado 
**E** o curso deve ser exibido na página de listagem de cursos.


### Funcionalidade: Listar cursos disponíveis

**Como** usuário do Beedoo QA Challenge
**Quero** visualizar a lista de cursos disponíveis,
**Para que** eu visualizar suas informações.

| #   | REGRAS DE NEGÓCIO |
|-----|-------------------|
RN001 | A listagem de cursos deve exibir as informações do curso, como Nome do Curso, Descrição, Data Início, Data Fim, Número de vagas e Tipo do Curso.
RN002 | Deve possuir um botão com a opção de deletar o curso listado.


**Critérios de Aceite:**
**Dado** que o usuário esta na página de listagem de cursos,
**Então** todos os cursos cadastrados são exibidos.


### Funcionalidade: Excluir Curso

**Como** usuário do Beedoo QA Challenge
**Quero** deletar um curso da cadastrado,
**Para que** ele não esteja mais disponível para visualização.

| #   | REGRAS DE NEGÓCIO |
|-----|-------------------|
RN001 | A ação de deletar deve solicitar uma confirmação antes de excluir o curso permanentemente.
RN002 | Ao deletar um curso, este deve ser removido da listagem de cursos de forma dinâmica, sem necessidade de se atualizar a página.

**Critérios de Aceite:**
**Dado** que estou na página de listagem de cursos,
**Quando** deletar um curso
**Então** o curso deve ser removido da listagem.

## Plano de Teste

## Bug Report

