# jenkins_docker_project
the project involves the use of Jenkins and Docker. The project includes a Jenkins file, 
which prompts the user to enter the name of a file. Once the user enters the file name, Jenkins 
creates a container using the Docker image of Apache HTTP Server (httpd) and configures the file 
as the index.html for the website hosted by the container. This allows the user to easily create a container
with their desired index file for the website.

* It contains four basic html files (c, java, python and all)
* Dockerfile that designed to create an apache image (httpd) while using the selected index file
* The Jenkinsfile prompts for email, index file, and port and uses that information to build and run the container,
  with the specified index file and port. It also sends an email with the process status.


#It is important for the program to work, to configure this on the server before running: sudo chmod 666 /var/run/docker.sock
