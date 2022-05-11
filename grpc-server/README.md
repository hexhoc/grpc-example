# grpc-example

## Create grpc server. Step by step
1. Add grpc dependencies and plugin in pom.xml

   <artifactId>grpc-netty-shaded</artifactId>

   <artifactId>grpc-protobuf</artifactId>

   <artifactId>grpc-stub</artifactId>

   <artifactId>javax.annotation-api</artifactId>

2. Create **src/main/proto** folder and add **GreetingService.proto** file
3. Compile project
4. Create class GreetingServiceImpl that extend GreetingServiceGrpc.GreetingServiceImplBase
5. Override greeting() method
6. Start grpc server in main class