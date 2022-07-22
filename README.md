# Apine Docker

## Pull Docker
```
docker pull x3platform/apline
```

## Build Docker
```
# login
docker login -u [USERNAME] -p [PASSWORD]

docker buildx build --push --tag x3platform/alpine:latest --platform linux/amd64,linux/arm64 --file Dockerfile . 
```
