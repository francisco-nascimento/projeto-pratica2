## Atividade 10 :: Atividade final da 1a. Unidade
#### Missão: Definir tema do projeto e criar as páginas de Login e Novo usuário. 

1. Criar o template para a página inicial (página de login) de um sistema usando o Pingendo (<a href="Template-PaginaInicial.png">modelo</a>)
2. Definir e criar uma tabela no banco de dados para armazenar os usuários
3. Criar uma página para cadastrar um novo usuário (utilizar o Bootsnipp para gerar o formulário).
3. Implementar estas funcionalidades usando Java, Servlet, JSP e JDBC (observar as regras definidas abaixo).
4. Implementar testes unitários para o método de verificação de senha forte.
5. Disponibilizar todo o código-fonte num repositório do Github.

###### Funcionalidade 01: Efetuar Login

* A página inicial do sistema terá um campo para o login, um para senha, um link para o usuário solicitar uma nova senha e um outro link para fazer o cadastramento de um novo usuário.
* Todas as demais páginas do sistema só poderão ser acessadas após o usuário ter preenchido um login e senha válidos.
* O sistema deverá registrar a data/hora do último login realizado pelo usuário.
 
###### Funcionalidade 02: Cadastrar usuário

* O sistema deverá permitir a solicitação de um novo usuário na página inicial.
* O usuário deverá informar seu nome, login, email, cpf, senha e repetição da senha para efetuar o cadastro.
* Caso algum desses campos não seja informado, deverá ser apresentado ao usuário uma mensagem de erro.
* Só serão aceitas senhas com o seguinte critério de robustez: mínimo de 6 caracteres, existência de pelo menos um número e uma letra maiúscula.
* Os dados informados pelo usuário deverão ser armazenados no banco de dados.

