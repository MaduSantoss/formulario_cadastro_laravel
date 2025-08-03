**📋 Formulário de Cadastro com Laravel**

Este projeto é uma implementação simples de um formulário de cadastro de usuário utilizando o Laravel, ideal para estudo e prática com o framework PHP.

  

**🧪 Funcionalidade do Projeto**

- Tela simples de cadastro de usuário
- Validações básicas de formulário
- Estrutura padrão do Laravel (MVC)

  

**✅ Requisitos**

Certifique-se de ter as seguintes dependências instaladas em sua máquina:

- PHP 8.2 ou superior
- Composer (gerenciador de dependências do PHP)
- Node.js 22 ou superior
- MySQL (ou outro banco de dados suportado pelo Laravel)

  

**⚙️ Como configurar e executar o projeto**

1. **Clonar o repositório**
   ```bash
   git clone https://github.com/MaduSantoss/formulario_cadastro_laravel
   ```

2. **Copiar e configurar o arquivo .env**
   ```bash
   cp .env.example .env
   ```
   - Edite o arquivo `.env` com as configurações do seu banco de dados.

3. **Instalar as dependências do PHP**
   ```bash
   composer install
   ```

4. **Gerar a chave da aplicação**
   ```bash
   php artisan key:generate
   ```

5. **Rodar as migrações do banco de dados (se houver)**
   ```bash
   php artisan migrate
   ```

6. **Instalar dependências do frontend**
   ```bash
   npm install
   ```

7. **Rodar o servidor local**
   ```bash
   php artisan serve
   ```

Acesse o projeto no navegador:
👉 [http://127.0.0.1:8000](http://127.0.0.1:8000)

  

**🚀 Criando um projeto Laravel do zero (caso queira replicar)**

```bash
composer create-project laravel/laravel .
php artisan serve
```
