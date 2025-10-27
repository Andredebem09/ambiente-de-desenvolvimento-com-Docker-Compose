# Imagem base Node.js, versão LTS com Alpine
FROM node:lts-alpine

# Define o diretório de trabalho
WORKDIR /app

# Copia os arquivos de dependências
COPY package*.json ./

# Instala as dependências
RUN npm install

# Copia o resto do código da aplicação
COPY . .

# Expõe a porta padrão do NestJS
EXPOSE 3000

# Inicia a aplicação em "watch mode" para recompilar automaticamente em desenvolvimento
CMD ["npm", "run", "start:dev"]