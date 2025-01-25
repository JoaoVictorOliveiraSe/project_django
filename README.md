# project_django

Projeto Estoque de Revenda de Carros - Django

Passo a Passo do projeto:

1 - Criando ambiente virtual
Comando > python -m venv venv

Ativando ambiente virtual
Comando > .\venv\Scripts\activate

2 - Instalar pacotes e dependencias do Django
Comando > pip install django

3 - Ativando o projeto Django
Comando > django-admin startproject app .

4 - Verificando conexão com o django
Comando > python manage.py runserver

5 - Criando primeira APP
Comando > python manage.py startapp cars

6 - Inicializando o banco de dados do Django
Comando > python manage.py makemigrations

7 - Executando e criando todas as estruturas de banco de dados
Comando > python manage.py migrate

- Criando superuser (Super Usuario) username e passworld
Comando > python manage.py createsuperuser

- Nessa etapa vamos criar nosso nome de usuario, email e senha para acessar o dashboard do Django.

8 - Criando nosso modelo (Car)

Dentro do app Cars, vamos criar nosso primeiro modelo, acessando o arquivo models.py
Aqui nessa etapa vamos criar a classe e todos os campos da nossa tabela Car, contendo os registos das caracteristicas de carros.

9 - Atualizando o banco de dados com os comandos makemigrations e migrate

10 - Configurando o arquivo admin.py de cars
