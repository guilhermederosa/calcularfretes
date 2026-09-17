# 1 - Criar a pasta backend
mkdir backend
# 2 - Dentro da pasta, criar arquivo server.js
# 3 - Criar o arquivo package.json
npm init -y
# 4 - Instalar dependencia do express
npm install express
# 5 - Instalar dependencia de requisição de dominio
nm install cors
# 6 - Instalar dependencia para deixar o servidor rodando sempre
npm install nodemon
muda o "start": "nodemon server.js"
e no terminal digita: npm run start