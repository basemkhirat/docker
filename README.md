## Docker App

A template to run php apps on docker.

#### Folder Structure

`docker-compose.yml` is the main docker-compose file.

`containers`: folder to define Docker files.

`data` folder to store databases files.

`etc` folder to modify configuration files.

`log` folder to view log files.

`www` folder to add PHP app.

#### Installation

```bash
$ git clone https://github.com/basemkhirat/docker.git
$ cd docker
$ docker-compose build
$ docker-compose up -d
```

Browse http://localhost from a web browser.

That's all :)




