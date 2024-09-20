
## Docker-Interview:  

### What is Docker ?
  
Docker is a open source platform used to automate the dpeloyment of applications,within the lightweight and portable containers.
These containers package software and all its dependencies into standardized units, allowing applications to run consistently across different environments.

### Difference b/w container and virtual machine ?

1.Container is a lightweight.

2.Isolated environment that runs on a shared os kernel.

3.It allows faster startup times and reduced resource overhead compared to VM's.

1.VM, on the other hand, emulat ean entire physical computer.

2.Includes its own operating system.

3.The resources are required more to run.

### What is a docker image ?

A Docker image is a read-only template used to create docker containers.
It contains everything needed to run a software application, including code, runtime, libraries, and dependencies.
Images are built using a Dockerfile and can be stored in the Docker registries like Docker hub.

### Explain the role of a Dockerfile ?

A Dockerfile is a text file that contains instructions for building a Docker image.
It specifies the base image, commands to install dependencies, configure settings, and define how application should run inside the container.
Dockerfiles are used with docker build command to create custom Docker images.

### What is docker-compose and how it is used ?

1.Docker-compose is a tool used to define and run multi-container Docker applications.
2.It uses a YAML file to specify services, networks and volumes for an application, allowing developers to define and manage complex application environments with ease.


```
docker ps
```

![D](https://www.cherryservers.com/v3/assets/blog/2021-10-13/01.png)
