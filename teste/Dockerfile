# Usar a imagem oficial do Node.js versão 22
FROM node:22

# Definir o diretório de trabalho dentro do container
WORKDIR /usr/src/app

# Copiar o package.json e o package-lock.json para o diretório de trabalho
COPY package*.json ./

# Instalar as dependências do projeto
RUN npm install

# Copiar o código-fonte da aplicação para dentro do container
COPY . .

# Expor a porta onde a aplicação vai rodar (3000)
EXPOSE 3000

# Comando para rodar a aplicação
CMD [ "npm", "start" ]
