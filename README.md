## COMANDOS

** Executa o build do Dockerfile usando a tag franciscogoncalez/debian-http **

docker build -t franciscogoncalez/debian-http

** Executa a imagem franciscogoncalez/debian-http **

docker run -p 80:80 -d franciscogoncalez/debian-http
