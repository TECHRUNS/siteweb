# siteweb
Site web Projet
To lunch conteneur image with nginx execute this commande
docker run --name techruns -v $(pwd):/usr/share/nginx/html/ -p 80:80 -d nginx
