FROM n8nio/n8n:latest

# Instalar dependências necessárias
RUN apk add --no-cache bash curl

# Criar pasta de configuração do n8n
RUN mkdir -p /home/node/.n8n && chmod 700 /home/node/.n8n

# Definir diretório de trabalho
WORKDIR /data

# Expor a porta do n8n
EXPOSE 5678

CMD ["n8n"]
