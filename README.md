# micro-compose
a docker-compose.yml to quickly spin up a consul + micro api + micro sidecar + micro web environment.

This is a shameless *copy/paste* from [here] (https://micro.mu/docs/deploy-docker.html) and updated it to V2 syntax.

## For quick microservice infused fun

1. clone this repo 
2. run it with `$ docker-compose up` and see the pretty text lines fly by
3. open https://micro.mu in your browser of choice
4. ????
5. PROFIT!

## Where stuff is running

In case your lazy like me, you don't wanna read the source, so here's the gist:

* consul web interface is on port `8500`
* micro api is on port `8080`
 * stats web interface is on `8080/stats`
* micro web interface  is on `8082`

there's more but for that... quit being lazy!
