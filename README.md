## README.md - Dashboard de Funcionários

### Introdução

Este repositório contém o código-fonte de um dashboard administrativo simples para gerenciar uma lista de funcionários. O dashboard permite a criação, leitura, atualização e exclusão de registros de funcionários.

### Tecnologias Utilizadas

* **Frontend:**
    * React com Next.js
    * Chakra UI para estilização e componentes de UI
    * TypeScript para segurança de tipos
* **Backend:**
    * Node.js com Express.js
    * MongoDB (Mongoose) para banco de dados

### Funcionalidades

* **Página Inicial do Dashboard:**
    * Exibe uma tabela de funcionários com colunas para nome, cargo, departamento e ações (editar/excluir).
    * Inclui um botão para adicionar um novo funcionário.
    * Implementa funcionalidade de ordenação e busca na lista de funcionários.
* **Página de Adicionar Funcionário:**
    * Fornece um formulário para adicionar um novo funcionário com campos para nome, cargo, departamento e data de admissão.
    * Valida os campos do formulário antes de enviar.
* **Página de Editar Funcionário:**
    * Oferece um formulário para editar os detalhes de um funcionário existente.
    * Preenche o formulário com os detalhes atuais do funcionário.
    * Valida os campos do formulário antes de enviar.
* **API do Backend:**
    * Implementa endpoints RESTful para operações CRUD:
        * `GET /api/employees` - Recupera todos os funcionários.
        * `GET /api/employees/:id` - Recupera um único funcionário pelo ID.
        * `POST /api/employees` - Cria um novo funcionário.
        * `PUT /api/employees/:id` - Atualiza um funcionário pelo ID.
        * `DELETE /api/employees/:id` - Exclui um funcionário pelo ID.

### Detalhes Técnicos

* **Frontend:**
    * Utiliza componentes do Chakra UI para elementos de formulário, botões, tabelas e layout.
    * Garante que a aplicação seja responsiva.
* **Backend:**
    * Emprega Mongoose para interagir com o MongoDB.
    * Valida os dados antes de salvar no banco de dados.
    * Trata erros de forma adequada e retorna os códigos de status HTTP apropriados.
* **Geral:**
    * O código é escrito de forma limpa, legível e bem documentado.
    * O Git é usado para controle de versão.
    * O projeto está disponível em um repositório público no GitHub.
    * Um arquivo README.md inclui instruções sobre como configurar e executar a aplicação.

### Licença

Este projeto está licenciado sob a licença [MIT](https://opensource.org/licenses/MIT).


## Project Specifics | Test Requirements

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
