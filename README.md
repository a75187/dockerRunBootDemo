# docker4springboot
基于不改动原有spring-boot项目，将spring-boot项目搭建成docker项目


spring-boot-maker ： 基本的spring-boot项目

docker-maker ： docker项目

 docker run --name longorder-b  -d   --add-host mshz.eureka1:192.168.0.243  --add-host mshz.eureka2:192.168.0.243    -it -p 51703:51703 5cf14d9e0b4d
 增加host映射
