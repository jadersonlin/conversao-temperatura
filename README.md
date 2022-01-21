
## Iniciativa Kubernetes
### Aula 1

Comando para montar imagem no diretório __src__:

```` 
docker image build -t jadersonlin/conversao-temperatura:v1 .
`````

Comando para executar container:

````
docker container run -d -p 8080:8080 jadersonlin/conversao-temperatura:v1
`````
