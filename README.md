
# Ecomm Project


Um sistema de e-commerce desenvolvido com PHP e Laravel. Este projeto foi criado para gerenciar produtos, pedidos e clientes de maneira eficiente em um ambiente de loja online.

## Índice

- [Ecomm Project](#ecomm-project)
  - [Índice](#índice)
  - [Visão Geral](#visão-geral)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Funcionalidades](#funcionalidades)
  - [Instalação](#instalação)
    - [Pré-requisitos](#pré-requisitos)
    - [Passo a Passo](#passo-a-passo)
  - [Configuração](#configuração)
  - [Uso](#uso)
    - [Admin Dashboard](#admin-dashboard)
    - [Funcionalidades do Usuário](#funcionalidades-do-usuário)
  - [Contribuições](#contribuições)
  - [Licença](#licença)
  - [Contato](#contato)

## Visão Geral

O **Ecomm Project** é uma aplicação web completa para gestão de e-commerce. Com esta plataforma, os administradores podem gerenciar o catálogo de produtos, processar pedidos, e monitorar clientes, enquanto os usuários podem navegar pelos produtos, adicionar itens ao carrinho e realizar compras de maneira segura.

## Tecnologias Utilizadas

- **PHP**: Linguagem de programação principal.
- **Laravel**: Framework utilizado para o desenvolvimento do backend.
- **MySQL**: Sistema de gerenciamento de banco de dados.
- **Blade**: Motor de template do Laravel para renderização do frontend.
- **HTML/CSS/JavaScript**: Tecnologias padrão para construção da interface web.
- **Bootstrap**: Framework de front-end para design responsivo.

## Funcionalidades

- **Gestão de Produtos**: Adicionar, editar, remover e categorizar produtos.
- **Gestão de Pedidos**: Processamento e acompanhamento de pedidos.
- **Gestão de Clientes**: Registro, autenticação e perfil de clientes.
- **Carrinho de Compras**: Adição, remoção e atualização de itens no carrinho.
- **Checkout**: Processo seguro de checkout com opções de pagamento.
- **Admin Dashboard**: Painel administrativo para gerenciar o e-commerce.

## Instalação

### Pré-requisitos

- **PHP** >= 7.3
- **Composer**
- **MySQL** ou outro banco de dados compatível
- **Node.js** e **NPM** para compilação de assets

### Passo a Passo

1. **Clone o repositório:**
   \`\`\`bash
   git clone https://github.com/ronanfariaa/ecomm_project.git
   cd ecomm_project
   \`\`\`

2. **Instale as dependências do PHP:**
   \`\`\`bash
   composer install
   \`\`\`

3. **Instale as dependências do Node.js:**
   \`\`\`bash
   npm install
   \`\`\`

4. **Compile os assets do frontend:**
   \`\`\`bash
   npm run dev
   \`\`\`

## Configuração

1. **Copie o arquivo `.env.example` para `.env`:**
   \`\`\`bash
   cp .env.example .env
   \`\`\`

2. **Configure as variáveis de ambiente no arquivo `.env`:**
   - Defina as credenciais do banco de dados (DB_DATABASE, DB_USERNAME, DB_PASSWORD).
   - Ajuste outras configurações conforme necessário (APP_URL, MAIL_USERNAME, etc.).

3. **Gere a chave da aplicação:**
   \`\`\`bash
   php artisan key:generate
   \`\`\`

4. **Execute as migrações e seeders:**
   \`\`\`bash
   php artisan migrate --seed
   \`\`\`

5. **Inicie o servidor de desenvolvimento:**
   \`\`\`bash
   php artisan serve
   \`\`\`

   O servidor estará disponível em `http://localhost:8000`.

## Uso

### Admin Dashboard

- Acesse o painel administrativo através de `http://localhost:8000/admin`.
- Use as credenciais criadas ou, se você utilizou um seeder, as credenciais padrão são:
  - **Email:** `admin@ecomm.com`
  - **Senha:** `password`

### Funcionalidades do Usuário

- **Navegação de Produtos:** Os usuários podem navegar e buscar produtos disponíveis.
- **Carrinho e Checkout:** Adicione produtos ao carrinho e siga o processo de checkout.
- **Gerenciamento de Perfil:** Os usuários podem criar uma conta e gerenciar suas informações pessoais.

## Contribuições

Contribuições são bem-vindas! Se você deseja contribuir com o projeto, siga os passos abaixo:

1. **Fork o repositório**.
2. **Crie uma branch para sua feature** (\`git checkout -b minha-feature\`).
3. **Commit suas alterações** (\`git commit -m 'Adiciona minha feature'\`).
4. **Push para a branch** (\`git push origin minha-feature\`).
5. **Abra um Pull Request**.

## Licença

Este projeto é licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para qualquer dúvida ou sugestão, entre em contato:

- **Nome:** Ronan Faria
- **Email:** [ronanfariaa@gmail.com](mailto:ronanfariaa@gmail.com)
- **GitHub:** [ronanfariaa](https://github.com/ronanfariaa)

---

