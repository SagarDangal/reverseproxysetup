docker build -t app .
docker run -d p 8080:8080 app java -jar  demo-0.0.1-SNAPSHOT.jar
