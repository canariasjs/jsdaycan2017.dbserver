# Movies server based on json-server

This testing server contains data about movies, directors, writers, actors, actresses and genres.

The server working is based on the [json-server](https://github.com/typicode/json-server) tool which provides us a functional REST API in order get and presisting data.

All data handled by this server is contained on a [JSON](db/data.json) file and its structure is next:

![DB Structure](images/repository/db-structure.png)

In order to work with this server, it's needed to follow the next steps:

```sh
$ git clone https://github.com/ddialar/js.json-server.movies.git movies-server
$ cd movies-server
$ npm install
$ npm run json_server
```

These actions will run the server and its REST API that will be available via web browser through the URL `localhost:3000/`.

![Server running up](images/repository/server-running-up.png)