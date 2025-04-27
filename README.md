# DevClub Fullstack – API & Frontend

Projeto fullstack inspirado em “Criando uma API do ZERO com Node.js e Banco de Dados” e “Aprendendo React do Zero, Conectando Back e Front End” do canal DevClub Programação  .

## Tecnologias  
Node.js, Express, Prisma ORM + MongoDB ; React (hooks, fetch) .

## Instalação  
1. git clone  
2. cd backend && npm install && cp .env.example .env && npm start :contentReference[oaicite:0]{index=0}  
3. cd ../frontend && npm install && npm start   

## Endpoints API  
GET /users → lista usuários (200)   
GET /users/:id → usuário por ID (200/404)  
POST /users → cria usuário (201/400)  
PUT /users/:id → atualiza usuário (200/400/404)  
DELETE /users/:id → remove usuário (200/404)   

## Modelo de Dados  
Prisma schema User { id, name, email, age } com validação Joi: name ≥4, email válido, age ≥0  .

## Front-end  
React monta em index.html via Vite; componentes em src/, assets em src/assets; .env para API_URL  .

## References   
– DevClub Programação videos (Node & React)   
