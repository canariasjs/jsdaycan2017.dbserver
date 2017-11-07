# Servidor de Películas basado en json-server

[English version](README.EN.md)

Servidor para pruebas que contiene información acerca de películas, directores, guionistas, actores, actrices y géneros cinematográficos.

Su funcionamiento está basado en la herramienta [json-server](https://github.com/typicode/json-server) la cual, nos proporciona una API REST funcional para poder consumir y almacenar datos.

La información manejada por este servidor se encuentra almacenada en un archivo [JSON](db/data.json) y se está estructurado de la siguiente manera:

![DB Structure](images/repository/db-structure.png)

Para iniciar el servidor, se deben llevar a cabo los siguientes pasos:

```sh
$ git clone https://github.com/canariasjs/jsdaycan2017.dbserver.git dbserver
$ cd dbserver
$ npm install
$ npm run json_server
```

Esto iniciará el servidor y su API REST será accesible desde un navegador web a través de la URL `localhost:3000/`, mostrando un resultado similar a este:

![Server running up](images/repository/server-running-up.png)