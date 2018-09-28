# Docker Spring boot App example

#### Clone hello-spring-boot
`git clone https://github.com/royalpay/hello-spring-boot.git`

#### Build hello-spring-boot docker image
`cd hello-spring-boot`

`mvn package`

`mvn dockerfile:build`

#### Run hello-spring-boot container
`docker run --name="hello-spring-boot" -p 8080:80 -d hello-spring-boot:0.1.0 `

#### Visit hello-spring-boot container

`curl http://localhost:8080`

