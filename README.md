# 📋 Sistema de Cadastro de Clientes

Um sistema completo para gerenciamento de clientes desenvolvido com Node.js, Express, MySQL e Sequelize.

## ✨ Funcionalidades Principais

- **Cadastro de clientes** com nome, cidade, estado, CEP e telefone
- **Listagem completa** de todos os clientes cadastrados
- **Busca inteligente** por nome, cidade ou telefone
- **Edição** e **exclusão** de registros
- Interface responsiva e moderna

## 🛠️ Tecnologias Utilizadas

- **Backend**: Node.js + Express
- **Banco de Dados**: MySQL (com Laragon)
- **ORM**: Sequelize
- **Template Engine**: EJS
- **Frontend**: CSS moderno com variáveis e design responsivo

## 🚀 Como Executar

1. **Pré-requisitos**:
   - Node.js (v18+)
   - MySQL (via Laragon)
   - Git (opcional)

2. **Instalação**:
   ```bash
   git clone https://github.com/isaaczinrs2/cadastro-clientes.git
   cd cadastro-clientes
   npm install
   npm install dotenv
   ```

3. **Configuração**:
   - Crie um arquivo `.env` (Opcional) 
   - Configure as credenciais do seu banco MySQL

4. **Execução**:
   ```bash
   node app.js
   ```
   Acesse: [http://localhost:3000](http://localhost:3000)

## 📦 Estrutura do Projeto

```
cadastro-clientes/
├── config/       # Configurações do banco de dados
├── controllers/  # Lógica das rotas
├── models/       # Modelos do Sequelize
├── public/       # Arquivos estáticos (CSS, JS)
├── routes/       # Definição de rotas
├── views/        # Templates EJS
├── app.js        # Aplicação principal
└── package.json  # Dependências
```
---

Desenvolvido por Isaac Amorim
