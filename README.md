# ECS796P-Lab1
Based upon grpc tutorial at https://github.com/eugenp/tutorials/tree/master/grpc
Commands for preparing the enviornment (Assuming you are in the main folder e.g. the one with the pom.xml file in it)
1. sudo apt update
2. sudo apt install git default-jdk maven
3. git clone https://
4. cd 
5. mvn clean package install
6. mvn exec:java -Dexec.mainClass="server.GrpcServer"
7. mvn exec:java -Dexec.mainClass="client.GrpcClient" (Need to run this from a seperate terminal or ssh connection)
