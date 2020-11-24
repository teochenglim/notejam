### Heroku

```shell
$ heroku login
$ heroku git:remote -a notejam-app
$ heroku create notejam-app
$ git add .
$ git commit -m "make it better"
$ git push heroku master

```

### Kubernetes version (WIP)

1. Choose Prometheus client using

https://pypi.org/project/flask-prometheus-metrics/

2. Build docker


```shell
docker build -t teochenglim/notejam . -f Dockerfile
docker push teochenglim/notejam:latest

```

3. run local instance using docker-compose

```shell
docker-compose up

```
