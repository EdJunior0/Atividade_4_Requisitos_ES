# Atividade 4 - Requisitos

O presente documento trata da Atividade 4 - Requisitos, da matéria de Engenharia de Software do curso de ciência da computação da Universidade Federal do Tocantins.

O intuito da atividade é a **definição de dois requisitos funcionais** de um sistema de software qualquer, a exemplificação documentada do **caso de uso expandido** e do **user story** de ambos os requisitos, bem como **fazer o protótipo** para tais.

## Os requisitos funcionais

Para o estudo da atividade, os requisitos funcionais abordados ao longo do documento serão:
- Tela de login;
- Tela de cadastro.

## User Story

As **User Stories** fazem parte da estrutura de uma estrutura ágil que basicamente **ilustram os recursos/requisitos de um software** em perspectiva do usuário ou cliente final.

Existem alguns modelos para se seguir ao criar as histórias de usuário, mas um dos mais famosos é o: **Como**, **eu quero**, **para que**.

1. **Como**: Tipo de usuário. Pode ser o cargo ou papel que o utilizador do software irá exercer;
2. **Eu quero**: Objetivo ou necessidade do usuário em questão;
3. **Para que**: Benefício em que o usuário terá ao atingir à necessidade requisitada.

### **User Story - Tela de Login**

“Como **um usuário já cadastrado no sistema** eu quero **fazer login com meu email e senha** para que **eu possa usufruir das ferramentas neles presente**.”

### **User Story - Tela de Cadastro**

“Como **um usuário novo do sistema** eu quero **poder criar uma nova conta com meu nome, email e senha** para que **eu possa ter uma nova conta e usufruir das ferramentas do mesmo**.”

## Caso de Uso Expandido

Basicamente, caso de uso é **um dos tipos de classificadores**, podendo representar uma unidade funcional provido pelo sistema ou subsistema.

Eles são narrativas em texto, que **podem descrever uma unidade funcional** e são bastante utilizados para representar **requisitos funcionais** nos sistemas.

### **Caso de uso expandido - Tela de Login**

#### **RQ01 - Tela de Login**

- **Atores:**
    - Usuário - Entra no sistema;

- **Descrição sucinta:**
	- Entra no sistema para que possa utilizar dos recursos disponíveis;

- **Pré-condição:**
	- O(s) ator(es) já deve ter criado uma conta no sistema.

- **Fluxo principal:**
	1. O ator ao abrir o sistema o mesmo apresenta ao auto a tela de Login;
	2.  A aplicação dispõe ao autor um formulário com Email e Senha para preencher;
	3. Ao preencher ambos os campos o autor confirma os dados no botão de “entrar”;

- **Campos do Formulário:**
    Campo     | Obrigatório? | Editável? | Formato
    --------- | ------------ | --------- | -------
    Email     | Sim          | Sim       | Texto
    Senha     | Sim          | Sim       | Texto

- **Opções do Usuário:**
    Opção     | Descrição               | Atalho   
    --------- | ------------            | -------
    Entrar    | Confirmar email e senha |       

- **Relatório do Usuário:**
    Campo     | Descrição    | Formato   
    --------- | ------------ | -------
    --        | --           | --   

- **Fluxos alternativos:**

    **FA01 -** Botão de “Não tenho uma conta”:
    1. O autor ao clicar no botão “Não tenho uma conta” na tela de Login, o autor é direcionado para a tela de Cadastro;

### **Caso de uso expandido - Tela de Cadastro**

#### **RQ02 - Tela de Cadastro**

- **Atores:**
    - Usuário - Cria uma conta no sistema;

- **Descrição sucinta:**
	- Cria uma nova conta no sistema para que possa utilizar dos recursos disponíveis;

- **Pré-condição:**
	- O(s) ator(es) não deve(m) ter conta criada no sistema.

- **Fluxo principal:**
	1. O ator ao abrir o sistema o mesmo apresenta ao auto a tela de Login;
	2. Nessa tela é disposta um botão com título “Não tenho uma conta” que redireciona o usuário à tela de Cadastro;
	3. A aplicação dispõe ao autor um formulário com Nome, Email e Senha para preencher;
	4. Ao preencher os campos o autor confirma os dados no botão de “criar conta”;

- **Campos do Formulário:**
    Campo     | Obrigatório? | Editável? | Formato
    --------- | ------------ | --------- | -------
    Nome      | Sim          | Sim       | Texto
    Email     | Sim          | Sim       | Texto
    Senha     | Sim          | Sim       | Texto

- **Opções do Usuário:**
    Opção       | Descrição                 | Atalho   
    ---------   | ------------              | -------
    Criar conta | Confirmar Dados inseridos |       

- **Relatório do Usuário:**
    Campo     | Descrição    | Formato   
    --------- | ------------ | -------
    --        | --           | --      

- **Fluxos alternativos:**

    **FA01 -** Botão de “Não tenho uma conta”:
    1. O autor ao clicar no botão “Já tenho uma conta” na tela de Cadastro, o autor é direcionado para a tela de Login;

## **Protótipo**

- https://www.figma.com/file/hZS3FT2XP2Q4Pib4LaDEHL/Atividade-4%3A-Requisitos---Edson?node-id=0%3A1
