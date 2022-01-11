
			Readme



Instalação Projeto Sobra Quanto

-----------Programas----------

Composer
NodeJS
xampp
GitKraken
-----------------------------------
(Abra o xampp, inicie apacha e mysql)

No GitKraken, faça o clone do repositorio, e abra o VScode

Abra o terminal do VsCode e acesse a pasta do SobraQuanto (xampp/htdocs/SobraQuanto/SobraQuanto/)

Digite. composer install
Depois, composer update
npm install 
npm run dev

cp .env.example .env

php artisan key:generate 

config .env (Criar banco de dados)
(alterar, app name, DB_DATABASE)




php artisan migrate:fresh 

Parar iniciar o sistema 

php artisan serve
