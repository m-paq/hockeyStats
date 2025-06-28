# Running with docker

## Docker Installation

If you do not have docker installed, see the following [documentation](https://docs.docker.com/engine/install/).

You might need to also install `docker-compose` if you do not currently have it installed.

## Running the App

Once the app is ready to run, execute the following commands:

``` bash
docker build -t hockey-stats .
docker-compose up
```

After that, the app should be running.

## PS

You might need to recheck the ports you are using as the dockerization maps the port 3000 (of the server) to the local port 8080 (localhost port).
*i.e.* You should poke the server throught `localhost:8080` for the home page.
