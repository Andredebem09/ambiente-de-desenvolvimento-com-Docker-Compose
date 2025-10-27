# Imagem base oficial e leve do Nginx
FROM nginx:alpine

# Remove o arquivo de configuração padrão do Nginx
RUN rm /etc/nginx/conf.d/default.conf

# Copia o nosso arquivo de configuração personalizado para o local correto
COPY nginx.conf /etc/nginx/conf.d