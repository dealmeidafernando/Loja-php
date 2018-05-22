# Loja-php
Loja php. O usuário logado pode adicionar, remover, listar produtos e enviar contato para loja.

# Configurando o ambiente Windows:
* Download do projeto 
* Baixar e instalar o [Xampp](https://www.apachefriends.org/download.html) seguindo o passo a passo do instalador
* Start nos serviços `PHP`, `APACHE` e `MYSQL`
* Acessar o Mysql localmente através do [endereço](http://localhost/phpmyadmin) ou http://localhost/phpmyadmin e criar o banco "loja" 
* Entrar na pasta do projeto baixado **dumps** > **Dump20180522** copiar todos os arquivos **.sql** para pasta do `mysql` em sua máquina
* Copiar todo o projeto e colar em **C:/xampp/htdocs**
* Para que a conexão com banco de dados funcione, altere o arquivo do projeto **conecta.php** para 

  `$conexao = mysqli_connect("localhost", "root", "", "loja");`
