# Product API

Go based Product API built using the Gorilla Toolkit [https://www.gorillatoolkit.org/](https://www.gorillatoolkit.org/)

git 

## Running

The applicaiton can be run with `go run`

```
➜ go run main.go
products-api 2020/02/16 16:15:11 Starting server on port 9090

curl localhost:9090/products


curl -v localhost:9000/1 -XPUT  -d '{"name": "tea", "decription": "a nice cup of tea"}' | jq

curl localhost:9000 | jq

```
