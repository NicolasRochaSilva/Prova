# Prova
Ferramentas:

 - VSCode

 - WAMP ( com phpmyadmin )

 - Composer

tecnologias usadas:

 - Backend: 
   * PHP;
   * Symfony;
   * Mysql;

 - FrontEnd 
   * HTML; 
   * CSS; 
   * JS; 
   * Jquery; 
   * Ajax;
   * Bootstrap;
	
Enunciado:

1 - Criar um banco de dados chamado "empresa" no phpmyadmin usando mysql

2 - Criar uma tabela no banco de dados chamada "usuarios" com as colunas id, nome, data_de_nascimento, username e password

3 - Criar uma api com php/symphony que faça o cadastro do usuario recebendo todos os parâmetros necessários

4 - Criar uma api com php/symphony que valide o login do usuario

5 - Criar uma api com php/symphony que atualize os dados do usuario

6 - Criar uma api com php/symphony que busque os dados do usuario menos o password

7 - Criar uma tela de login

8 - Criar uma tela com CRUD de cadastro de usuario

9 - Criar uma tela pós login com os dados do usuario menos a senha   

Extra:

10 - senha deve ser armazenada encriptada em sha512

11 - apis php utilizando swagger

Comandos adicionais

na pasta C:\wamp64\www\teste executar o comando php -S localhost:8000 -t public

composer create-project symfony/skeleton nome-do-projeto

composer require symfony/framework-bundle

composer require symfony/framework-bundle symfony/http-kernel symfony/http-foundation symfony/routing symfony/dependency-injection symfony/config symfony/dotenv symfony/console

