# OmarDocker
##Dependencias:
- docker
- docker-machine
- docker-compose
##Para ejecutar:
```
docker-machine create --driver virtualbox dev
eval "$(docker-machine env dev)"
docker-compose up -d
```
Cuando realizamos cambios en los ficheros ejecutamos
```
	docker-compose build
	docker-compose up -d
	...
```
jueves, 28. enero 2016 12:25 

