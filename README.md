# spring-boot-docker-starter

```
# build
gradlew build

# run
gradlew bootRun
```

```
# image build & run
docker build . -t deploy-spring:0.0.1
docker run -d -p 8080:8080 --name deploy-spring deploy-spring:0.0.1

# docker-compose
docker-compose up -d
docker-compose down
```
