# ECS796P-Lab1
Based upon grpc tutorial at https://github.com/eugenp/tutorials/tree/master/grpc
Commands for preparing the enviornment (Assuming you are in the main folder e.g. the one with the pom.xml file in it)
1. sudo apt update
2. sudo apt install git default-jdk maven
3. git clone https://github.com/zky339/ECS796P-Lab1.git
4. cd ECS796P-Lab1
5. mvn clean package install
6. mvn exec:java -Dexec.mainClass="server.GrpcServer"
7. mvn exec:java -Dexec.mainClass="client.GrpcClient" 
