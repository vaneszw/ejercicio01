# ejercicio01
Resolución del ejercicio01 del curso de Docker

Comando para crear la imagen nginx:
docker run -p 8000:80 --name e01-nginx -v html:/usr/share/nginx/html:ro -d nginx

Luego para verificarlo:
docker ps


