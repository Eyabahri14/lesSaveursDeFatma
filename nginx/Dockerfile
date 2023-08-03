FROM nginx:alpine

# Copier votre nginx.conf à la bonne destination pour le fichier de configuration principal
COPY nginx.conf /etc/nginx/nginx.conf

# Copier votre nginx.conf à la bonne destination pour le fichier de site virtuel par défaut
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80
ENTRYPOINT ["nginx", "-g", "daemon off;"]
