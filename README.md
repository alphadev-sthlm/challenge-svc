
# Service startup

mvn spring-boot:run

# Example service usage

curl -H "Content-Type: multipart/form-data" --form json=@src/test/resources/recognition4.json --form file=@src/test/resources/recognition4.jp http://localhost:8080/challenge/anger
