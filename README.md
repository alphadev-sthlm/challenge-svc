
# Service startup [![Build Status](https://travis-ci.org/alphadev-sthlm/challenge-svc.png)](https://travis-ci.org/alphadev-sthlm/challenge-svc)

mvn spring-boot:run

# Example service usage

Run from challenge-svc root:

	curl -POST --form "json=@src/test/resources/recognition4.json;type=application/json" --form file=@src/test/resources/recognition4.jpg http://localhost:8080/challenge/anger -o ./response-img.jpg



