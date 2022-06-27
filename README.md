# docker_files
## Для nginx использовались команды (все собирается из готового образа):
1. sudo docker run -d nginx <br />
2. sudo docker ps <br />
3. sudo docker run -d -p 8080:80 --name my_nginx nginx <br />
4. sudo docker run -d -p 80:80 -v ${PWD}:/usr/share/nginx/html nginx <br />
