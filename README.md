# Pizzaria

## 👥 Integrantes da Dupla
- André Gustavo Pavanelli
- João Victor
                                                    


## 📖 Descrição do Projeto
Este projeto consiste no desenvolvimento de uma aplicação fullstack de uma pizzaria que cria e consulta o proprio banco de dados e API para a anotação e confirmação de pedidos dessa pizzaria além de ter uma aba propria para o garçom, atendente e adm. 

Garçom- É capaz de anotar os pedidos e visualizar suar respectivas mesas🍷

Atendente - Controle de gastos e acompanhamento dos pedidos💰

ADM - Controle de gastos e senhas dos funcionarios💻



A aplicação permite:
- realizar pedidos 
- Guardar esses pedidos em um banco de dados proprio
- calcular o faturamento
- mostrar o numero de: Clientes & Pizzas

## 💻 Tecnologias Utilizadas

### Backend
- Node.js
- Express
- sqlite
- json web token
- bcryptjs
- cors
- dotenv

#grande parte dessas tecnologias são bibliotecas ou frameworks que ajudam nas funcionalidades e segurança do site
  

### Frontend
- HTML 
- CSS 
- JavaScript



## ⚙️ Como Executar o Backend

1. Clone o repositório(git clone)
2. verificar se a ordem das pasta está correta
pastas:
<img width="250" height="557" alt="unnamed" src="https://github.com/user-attachments/assets/85606aeb-a6c4-48f3-9ac6-a5e9e0a43594" />


3. npm install express
4. npm install sql.js
5. npm install jsonwebtoken
6. npm install bcryptjs
7. npm install cors
8. npm install dotenv

9. popular o banco de dados com o comando (node seed.js)

10. iniciar o servidor (node index.js)

11. Acesse http://localhost:3001 no navegador.

tela de login:
<img width="1919" height="943" alt="unnamed" src="https://github.com/user-attachments/assets/40dcb08d-5973-4b0f-bd5b-be6d83685001" />


tela logada:
<img width="1919" height="935" alt="unnamed" src="https://github.com/user-attachments/assets/cd8049e8-907e-4055-bc77-2887b5bf1dfc" />


## 📁Estrutura de pastas

/.vscode
/node_modules
/public
├── index.html
├── script.js
└── style.css
/src
├── database/
│    └── sqlite.js
├── routes/
│    └── index.js
├── middleware/
│    └── sqlite.js
└── models/
├── Cliente.js
├── Pedido.js
├── Pizza.js
└── Usuario.js
.env
index.js
package-lock.json
package.json
pizzaria.db
seed.js


/public → Frontend (HTML, CSS, JS) 
/src /database → Conexão com o banco (SQLite)
/routes → Definição das rotas da API 
/middleware → Middlewares (ex: conexão com banco) 
/models → Entidades e regras de negócio 
index.js → Arquivo principal do servidor
.env → Variáveis de ambiente
pizzaria.db → Banco de dados 
SQLite seed.js → Popula o banco com dados iniciais










