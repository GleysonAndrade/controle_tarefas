Projeto Controle de Tarefas Laravel 8.5.9

Instalando laravel ui
### composer require laravel/ui:^3.2

Implementação do front end com bootstrap
### php artisan ui bootstrap --auth

Baixar os arquivos so node
### npm install

Gera as asstes do front end
### npm run dev




Teste durante o curso
### /**
### * //verifica se o usuário está autentica sem o uso do middleware auth
### * Recupera os dados do usuário autenticado
### * if(auth()->check()){
### * $id = auth()->user()->id;
### * $name = auth()->user()->name;
### * $email = auth()->user()->email;
### * return "ID: $id | Nome: $name | Email: $email";
### * }else{
### * return 'Você não está logado no sistema';
### * }
### */