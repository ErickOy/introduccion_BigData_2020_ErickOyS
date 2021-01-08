### Comandos básicos de docker

 

Docker es una herramienta de virtualización para levandar maquinas independientes con SO ligero y en poco tiempo.

 

```sh
$ docker run -i t <SO>
$ docker run -it -p <p.salida/p.interno><servicio>
$ docker ps
$ docker exec -it <id-container> cat <dirección del txt>
$ docker rm -f <id-container>

```