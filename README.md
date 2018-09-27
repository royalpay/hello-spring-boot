# Docker Spring App example

#### Clone hello-spring-boot
`https://github.com/royalpay/hello-spring-boot.git`

#### Build hello-spring-boot docker image
`cd hello-spring-boot`

`docker build -t hello-spring-boot .`

#### Run hello-spring-boot container
`docker run --name="hello-spring-boot" -p 8080:80 -d hello-node `

#### Visit hello-spring-boot container

`curl http://localhost:8080`

