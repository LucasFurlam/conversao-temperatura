# conversao-temperatura

Project that performs the conversion from Celsius to Fahrenheit and Fahrenheit to Celsius.

## Commands used in the docker to build the image and create the container

- docker image build -t furlam/conversao-temperatura:v1 .
- docker container run -d -p 8080:8080 furlam/conversao-temperatura:v1
