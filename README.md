# Shiny docker operator

##### Description

A simple example of a shiny docker operator.

```
https://github.com/tercen/shiny_docker_operator.git
```

##### Build

```bash
VERSION=0.10.0.1
docker build -t tercen/shiny_docker_operator:$VERSION .
docker push tercen/shiny_docker_operator:$VERSION
git add -A && git commit -m "$VERSION" && git tag  $VERSION  && git push && git push --tags
```
 
