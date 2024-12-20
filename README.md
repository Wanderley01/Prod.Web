# Prod.Web

Prod.Web é um sistema local para gerenciamento de produtos, vendas e funcionários, projetado para atender pequenas empresas e estabelecimentos locais. Com funcionalidades como cadastro de produtos, controle de estoque, registro de vendas, e acompanhamento de funcionários, ele oferece uma solução completa e fácil de usar.

## 🛠️ Funcionalidades

### Perfil **Dono (Admin)**
- Gerenciamento completo de produtos:
  - Cadastrar, editar, excluir produtos.
  - Criar categorias de produtos.
  - Precificar e adicionar notas sobre produtos.
- Controle de estoque e vendas.
- Cadastro e gerenciamento de funcionários:
  - Definir nomes e senhas para acesso.
  - Controlar permissões (funcionários têm acessos limitados).
- Acompanhamento de caixa:
  - Visualização das vendas realizadas.
- Relatório mensal:
  - Horas trabalhadas pelos funcionários.
  - Total arrecadado no mês.

### Perfil **Funcionário**
- Registro de vendas.
- Pesquisa de preços dos produtos cadastrados.
- Controle de ponto:
  - Registro de entrada e saída.
  - Relatório mensal com total de horas trabalhadas.

---

## 🎯 Objetivos do Sistema

O objetivo do Prod.Web é oferecer uma plataforma eficiente e simplificada para que pequenos negócios consigam:
- Acompanhar estoque e vendas sem complicações.
- Automatizar processos como cálculo de horas trabalhadas e registro de ponto.
- Garantir uma gestão organizada com dados centralizados localmente.

---

## 💻 Tecnologias Utilizadas

### **Frontend**
- [React.js](https://reactjs.org/) ou [Vue.js](https://vuejs.org/) - Para interface interativa e responsiva.
- [Bootstrap](https://getbootstrap.com/) ou [Tailwind CSS](https://tailwindcss.com/) - Para estilização da interface.

### **Backend**
- [Node.js](https://nodejs.org/) com [Express.js](https://expressjs.com/) - Para gerenciar APIs e lógica do servidor.
- [SQLite](https://www.sqlite.org/) - Banco de dados local leve e eficiente.
- [Sequelize](https://sequelize.org/) - ORM para simplificar operações no banco de dados.
- [JWT](https://jwt.io/) - Para autenticação e controle de permissões.

### **Empacotamento**
- [Electron](https://www.electronjs.org/) - Para transformar o sistema em uma aplicação desktop.

---

## ⚙️ Requisitos do Sistema

- **Node.js** instalado na máquina.
- **SQLite** configurado.
- **Git** para controle de versão.
- Sistema operacional compatível com aplicações Electron (Windows, macOS ou Linux).

---

## 🚀 Como Executar o Projeto

### **1. Clonar o Repositório**
```bash
git clone https://github.com/seu-usuario/prodweb.git
cd prodweb
