#### Welcome to The Readmme File for LoadBalancing project##########

##### Requirement ######
Apache Maven 3.6.3
java 11

###### Set up ######
sudo apt install maven
sudo apt-get install openjdk-11-jdk



###### Compile the app and generate the oar java file ######

mvn compile

mvn clean install

### Once the oar file generated (It's will be located in target/ directory) you can import it using the web interface for the onos controller
 
