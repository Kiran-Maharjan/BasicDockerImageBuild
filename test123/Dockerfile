#Use the OpenJDK 11 image as the base image
FROM openjdk:19

#Create a new app directory for my application files
RUN mkdir /app

#Copy the app files from host machine to image filesystem
COPY out/production/test123/ /app

#Set the directory for executing future commands
WORKDIR /app

#Run the Main class
CMD java Main

#run  this command in terminal to create image " docker build -t test123-image:1.0 ."
# docker images