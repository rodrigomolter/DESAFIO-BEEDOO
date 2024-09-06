# Desafio Beedoo 🐝
<div align="center">
  <img src="https://github.com/user-attachments/assets/90227214-deb4-4579-a4e9-33b49065a415" width="600">
  </br>
  <p> 
     O Desafio Beedoo tem o objetivo de avaliar os conhecimentos e habilidades em teste de software.
  </p>
</div><br>

O Desafio Beedoo oferece um conjunto de funcionalidades para o módulo de cursos. As funcionalidades incluem:

1. Criação de Novos Cursos
2. Exclusão de cursos criados
3. Listagem dos cursos criados

## Sumário
1. [User Stories 💁](#user-stories-)
2. [Plano de Teste 👨‍🔬](#plano-de-teste-)
3. [Bug Report 🐞](#bug-report-)
4. [Evidências 📂](#evidências-)


## User Stories 💁
As *User Stories* foram desenvolvidas com base nessas três funcionalidades de criar, listar e excluir. Suas regras de negócio foram baseadas nos campos disponibilizados na [aplicação sob teste](https://creative-sherbet-a51eac.netlify.app/).

### 1. Cadastrar novo curso

#### 1.1 User Storie
  
**Como** usuário do Beedoo QA Challenge,  
**Quero** cadastrar um novo curso,  
**Para que** ele possa ser listado na página de cursos.  

#### 1.2 Regras de Negócio

| #   | REGRAS DE NEGÓCIO |
|-----|-------------------|
RN001 | Devem estar disponíveis os campos "Nome do Curso", "Descrição do Curso", "Instrutor", "URL da Imagem da Capa", "Data de Início", "Data de Fim", "Número de Vagas", e "Tipo de Curso", sendo todos eles obrigatórios.
RN002 | O campo "Data Fim" deve possuir uma data igual ou posterior à "Data Início".
RN003 | O campo "Número de Vagas" deve ser um número inteiro positivo.
RN004 | O campo "Tipo do Curso" possuir apenas as opções "Presencial" e "Online".
RN005 | Caso o Tipo do Curso escolhido for "Presencial", o campo "Endereço" deverá ser exibido e é um campo obrigatório.
RN006 | Caso o Tipo do Curso escolhido for "Online", o campo "Link de Inscrição" deverá ser exibido e é um campo obrigatório.
RN007 | Ao cadastrar um novo curso, o usuário deve receber uma mensagem de confirmação de cadastro com sucesso, e ser redirecionado para a página de listagem de cursos.
RN008 | Deve se exibir de forma clara qual campo esta inválido


#### 1.3 Critérios de Aceite

**Dado** que o usuário esta na na página de cadastro de cursos,  
**Quando** ele preencher todos os campos obrigatórios corretamente,  
**E** clicar em "Salvar",  
**Então** o novo curso deve ser criado  
**E** o curso deve ser exibido na página de listagem de cursos.  

___

### 2. Listar cursos disponíveis

#### 2.1 User Storie  

**Como** usuário do Beedoo QA Challenge,  
**Quero** visualizar a lista de cursos disponíveis,  
**Para que** eu visualizar suas informações.  

#### 2.2 Regras de Negócio  

| #   | REGRAS DE NEGÓCIO |
|-----|-------------------|
RN001 | A listagem de cursos deve exibir as informações do curso, como Nome do Curso, Descrição, Data Início, Data Fim, Número de vagas e Tipo do Curso.
RN002 | Deve possuir um botão com a opção de deletar o curso listado.


#### 2.3 Critérios de Aceite

**Dado** que o usuário esta na página de listagem de cursos,  
**Então** todos os cursos cadastrados são exibidos.  

___
### 3. Excluir Curso

#### 3.1 User Storie

**Como** usuário do Beedoo QA Challenge,  
**Quero** deletar um curso da cadastrado,  
**Para que** ele não esteja mais disponível para visualização.  

#### 3.2 Regras de Negócio

| #   | REGRAS DE NEGÓCIO |
|-----|-------------------|
RN001 | A ação de deletar deve solicitar uma confirmação antes de excluir o curso permanentemente.
RN002 | Ao deletar um curso, este deve ser removido da listagem de cursos de forma dinâmica, sem necessidade de se atualizar a página.

#### 3.3 Critérios de Aceite

**Dado** que o usuário esta na página de listagem de cursos,  
**Quando** o usuário deletar um curso,  
**Então** o curso deve ser removido da listagem.  

## Plano de Teste 👨‍🔬

O plano de teste conta com o escopo trabalhado junto com a execução dos casos de testes.

[Plano de Teste - Beedoo QA Challenge](https://docs.google.com/spreadsheets/d/1PsArQFZ13y2IsFuKSXQPnaLIRTgnbyjhjXqkFay0ZOE/edit?usp=drive_link)

## Bug Report 🐞

[Bug Report - Beedoo QA Challenge](https://docs.google.com/spreadsheets/d/13fEWkz2abpgmCHLCIdRyCBnkSJEvdTn5P9v120qnrpI/edit?usp=drive_link)

## Evidências 📂
As evidências dos testes com sucesso e com falhas se encontram dentro das pasta de [Evidências](https://drive.google.com/drive/folders/1cDO_WuWiMwyif5GjNcgRO_3NLtKkPJij?usp=drive_link).  
As evidências também são referênciadas dentro do Bug Report.

[Evidências - Beedoo QA Challenge](https://drive.google.com/drive/folders/1cDO_WuWiMwyif5GjNcgRO_3NLtKkPJij?usp=drive_link)

___

Made with ❤️ by [Rodrigo Molter](https://www.linkedin.com/in/rodrigo-molter/).
