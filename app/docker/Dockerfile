# Usando imagem base do Node.js
FROM node:14-alpine

# Definindo variáveis de ambiente para o debug
ENV NODE_ENV=development
ENV PORT=3000

# Criando e definindo o diretório de trabalho
WORKDIR /app/frontend

# Copiando apenas os arquivos necessários para instalar as dependências
COPY /app/ ./

# Expondo a porta do frontend
EXPOSE 3000
