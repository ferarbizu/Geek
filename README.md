# Geek

## Laboratorio 1
Se implemento un maquedo del aplicactivo, en el cual solamelente se implemento con HTML, en este caso se utilizo Boostrap.

Dicho laboratorio se encuentra [aquí](https://github.com/ferarbizu/PaginaWeb).
## Laboratorio 2 y 3
Este laboratorio consistia en que se debia de elegir en Framework para poder desarrolar el Front-end de la aplicación el cual eligio **ReactJs**
Este laboratorio consta de 2 fases.
> Primera Fase: 
Se implemento el maquedado de la aplicación, los datos se alamacenaban en el *localstorage* donde solamente se coloco el metodo READ, que era para obetener los datos que el *localstorage* tenia.

> Segunda Fase: 
Se implementaron los metodos CRUD restantes.

## Laboratorio 4
Se realizo una aplicación en **NodeJs**, donde se realizaron 2 ejercicios introductorios el primer ejercico consiste en que apartir de una cadena que el usuario ingresaba, se analisaba si estaba correcta; el segundo ejercicio consistia en que el usuario ingresaba una URL con el siguiente formato `/hello/:name`, luego  de obtener lo que el usuario colocaba en esa estrucura se armaba un JSON `{ “hello”: “<name>”}` para mostrasrselo al usuario.

Dicho laboratorio se encuentra [aquí](https://github.com/ferarbizu/Labdoratorio-4/tree/master).

## Laboratorio 5
Se creo un proyecto con ExpressJs, el cual consistia en implementar una simulación de como funciona una aplicación RESTFul con sus 4 verbos http `POST, GET, PUT y DELETE`, estos se ejecutaban con la ruta `/api/V1/Cell/`, los datos se econtraban almacenados en una valiable local.

Dicho laboratorio se encuentra [aquí](https://github.com/ferarbizu/Laboratorio_5/tree/Lab5).

## Laboratorio 6
Se tenia que elegir un cliente para base de datos, en este caso de eligio **MongoDB** el cual se realizo de forma local, donde el RESTFul que se debia de poder comunicar con el cliente, y modificar los metodos para realizar la acciones en el cliente.

Dicho laboratorio se encuentra [aquí](https://github.com/ferarbizu/Laboratorio_5/tree/Lab6).

## Laboratorio 7
En este laboratorio de unio el Back-end con Front-end por medio de la dependencia `fetch`, luego de impemeto de un servio de **Redis** donde los datos de debia que pedir alli antes que del cliente de base de datos, esto para acceder los datos de una forma más rapida debido a que su funcionalidad es similar a la memoria RAM.

Dicho laboratorio se encuentra [Back-end](https://github.com/ferarbizu/Laboratorio_5/tree/Lab7).

## Laboratorio 8
Se creo un DockerFile para el Back-end y para el Front-end, luego se creo un `docker-compose.yml` para poder comunicar  las dependencia de Front-end, Back-end, Mongo y Redis, y asi mapear la aplicación al puerto `:8000`.

## Laboratorio 9
Con las imagenes de Docker generadas en el Laboratorio 8 se utilizaron para generar repositorios y colocarlos en las nubes correspondientes, se eligio AWS para Back-end(MongoDB, Redis y NodeJs), los pasos para realizar esto se encuentran [aquí](https://node.university/blog/10067/aws-ecs-containers), para MongoDB y para Redis, se realizo un procedimiento similar, ya que no se coloco ninguna variable environment y Google Cloud Plataform para el Front-end(React) los pasos se encuntran [aquí](https://medium.com/google-cloud/hosting-a-react-js-app-on-google-cloud-app-engine-6d1341b75d8c).
