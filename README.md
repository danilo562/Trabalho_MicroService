# Trabalho_MicroService
Para criar o pod no docker

Para criar um container nginx de serviço

1-)   docker run -d -e NGINX_ENTRYPOINT_QUIET_LOGS=1 nginx:1.21.1-alpine

Depois de Baixar a imagem 

2)   docker run --name "servirdor_web" -d -p 9092:80 -e NGINX_ENTRYPOINT_QUIET_LOGS=1 -v "C:\aplicacao:/usr/share/nginx/html" nginx:1.21.1-alpine

OBS: o caminho C:\Aplicacao é o caminho da minha maquina mude para onde esta a pasta na sua maquina

3)    Abra o novegador e colocar localhost:9092 que vai abrir tudo que esta dentro do conteiner.

se quiser ver o pod criar usar o comando DOCKER PS

