# GRPC_Client_Server

For the execution of this project : 
* to run the server : run "GrpcServer" in the directory "GRPC\src\main\java"
* to run the client : run "GrpcClient" in the directory "GRPC_Client\src\main\java"

Steps of realisation of this project:

**In the GRPC Server**
* Setting up the GRPC Environment in java using Maven (adding the required GRPC dependencies to the pom.xml file)
* Defining Services by creating Protocol Buffers (in the user.proto file)
* Generating Java stubs for ProtoBuffs using Maven Plugin
* Implementing GRPC services in Java (the userService class)
* Creating the GRPC Server class

**In the GRPC CLient**
* Setting up the GRPC Environment in java using Maven (adding the required GRPC dependencies to the pom.xml file)
* Generating the stubs using Maven Plugin in the client side
* Creating the GRPC Client class


**Execution of the Project**

*1- Running the GrpcServer*
![image](https://github.com/jazz-codes/GRPC_Client_Server/assets/152726047/dc9a9615-c709-45c3-9eca-93b196561947)

*2- Running the GrpcClient*
* in case of a successful login
![image](https://github.com/jazz-codes/GRPC_Client_Server/assets/152726047/d8f4a525-022d-4592-a08d-772da651d1c8)

* in case of an invalid password
![image](https://github.com/jazz-codes/GRPC_Client_Server/assets/152726047/aa94523c-dcf9-4603-b91a-615e933cadb0)

