Recomendação de Candidatos – Programa de Inclusão Profissional

Este projeto é um sistema web criado para facilitar o cadastro e a recomendação de candidatos Surdos em programas de inclusão no mercado de trabalho. Ele possui um formulário acessível e com validações, onde é possível enviar dados pessoais e documentos como currículo, laudo médico e histórico escolar, tudo seguindo as regras da LGPD.

Tecnologias

HTML5 e CSS3 – Interface simples, responsiva e acessível

SQLite3 – Banco de dados local e prático

Multer – Para upload seguro de arquivos

O que o sistema faz

Formulário completo para indicação de candidatos

Envio de arquivos com validação de formato e tamanho

Salvamento automático no banco SQLite

Organização dos documentos em pastas diferentes

Retorno em JSON para futuras integrações com um painel administrativo

🧠 Estrutura do Projeto
📁 recomendacao-candidatos
├── index.html
├── server.js
├── banco.db
└── uploads/
    ├── curriculos/
    ├── laudos/
    └── historicos/

🏁 Como rodar o projeto
npm install
node server.js


Ou:

npm init -y
npm install express multer sqlite3 sqlite cors
node server.js


Depois, é só acessar no navegador:
👉 http://localhost:3000
