# Docker_Basic

# Docker Container Vs Docker File Vs Docker Image:
Docker container :
Docker container is a running instance of a Docker image
•	The act of running a Docker image creates a Docker container
•	If You Build It, They Will Run (Usually)
•	Docker container is an instance of Docker images

Docker file:
•	A Dockerfile is a recipe ( blueprint) for creating Docker images
•	A Dockerfile is a text file that has instruction on how to build an images

Docker Image:
•	A Docker image is an immutable (unchangeable) file that contains the source code, libraries, dependencies, tools, and other files needed for an application to run.

•	Docker image as a class, where as a Docker container is an instance of that class.

The command for creating an image from a Dockerfile is docker build.
A Docker registry is a storage and distribution system for named Docker images.
A Docker repository is where you can store 1 or more versions of a specific Docker image.

Docker Vs Virtual machine: 
Docker is a software platform that simplifies the process of building, running, managing and distributing applications. It does this by virtualizing the operating system of the computer on which it is installed and running. Docker provides the ability to package and run an application 

	Docker is an open platform for developing, shipping, and running applications.
This makes Docker applications easier and more lightweight to deploy and faster to start up than virtual machines. Docker containers are generally faster and less resource-intensive than virtual machines.
Docker Hub is a service provided by Docker for finding and sharing container images with your team. Its like a github that holds all the images.

Here’s a List of Docker Commands
•	docker run – Runs a command in a new container.
•	docker start – Starts one or more stopped containers
•	docker stop – Stops one or more running containers
•	docker build – Builds an image form a Docker file
•	docker pull – Pulls an image or a repository from a registry
•	docker push – Pushes an image or a repository to a registry
•	docker export – Exports a container’s filesystem as a tar archive
•	docker exec – Runs a command in a run-time container
•	docker search – Searches the Docker Hub for images
•	docker attach – Attaches to a running container
•	docker commit – Creates a new image from a container’s changes
Check out the complete list of commands in the Docker documentation
 

