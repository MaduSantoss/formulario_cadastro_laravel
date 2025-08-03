📋 Formulário de Cadastro com Laravel
Este é um projeto simples desenvolvido com Laravel que apresenta um formulário de cadastro de usuário, ideal para fins de estudo e prática com o framework PHP mais popular atualmente.

🧪 Funcionalidade do Projeto
Tela simples de cadastro de usuário

Validações básicas de formulário

Estrutura padrão do Laravel (MVC)

✅ Requisitos
Certifique-se de ter as seguintes dependências instaladas em sua máquina:

PHP 8.2 ou superior

Composer (gerenciador de dependências do PHP)

Node.js 22 ou superior

MySQL (ou outro banco de dados suportado pelo Laravel)

⚙️ Como configurar e executar o projeto
1. Clonar o repositório
git clone https://github.com/MaduSantoss/formulario_cadastro_laravel

2. Copiar e configurar o arquivo .env
cp .env.example .env
Edite o arquivo .env com as configurações do seu banco de dados.

3. Instalar as dependências do PHP
composer install

4. Gerar a chave da aplicação
php artisan key:generate

5. Rodar as migrações do banco de dados (se houver)
php artisan migrate

6. Instalar dependências do frontend
npm install

7. Rodar o servidor local
php artisan serve

Acesse o projeto no navegador:
👉 http://127.0.0.1:8000

🚀 Criando um projeto Laravel do zero (caso queira replicar)
composer create-project laravel/laravel .
php artisan serve


