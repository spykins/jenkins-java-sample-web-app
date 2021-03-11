# SampleWebApp
This project is to test jenkins maven build, you can build this project locally to generate a target folder.

Note: You have to have Docker installed 

`docker run -it --rm --name my-maven-project -v "$(pwd)":/usr/src/mymaven -w /usr/src/mymaven maven:3.3-jdk-8 mvn clean install`

This will generate a target folder and you will see the SampleWebApp.war file generated there.