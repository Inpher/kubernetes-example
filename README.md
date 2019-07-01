# Example website

A basic html server, packaged with Docker. Static html files are placed in `static/`.

## Build

`docker build -t gcr.io/devops-interview-242708/nginx .`

## Run locally

`docker run --rm -p 8080:80 gcr.io/devops-interview-242708/nginx`

open localhost:8080 in a browser

## Deploy

`docker push gcr.io/devops-interview-242708/nginx`

`kubectl apply -f deploy.yaml`
