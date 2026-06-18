FROM nginx:1.27-alpine

# Собираем статический сайт внутрь nginx
COPY --chown=nginx:nginx . /usr/share/nginx/html

EXPOSE 80
