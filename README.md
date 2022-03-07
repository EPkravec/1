Simple web-server which uses postgresql database\
It does nothing except checking user / login and displaying static page.\
Deploy instruction for Ubuntu:

1. Install JDK 8

```
sudo apt install openjdk-8-jdk
```

1. Install maven

```
sudo apt install maven
```

1. cd into project root and build the project by this command

```
mvn clean package
``` 

Use this command to run the resulted jar

```
java -jar target/crud_mvp_demo.1.0.jar 
```
