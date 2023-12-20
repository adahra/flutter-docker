# How to dockerize Flutter apps

Presently, app development does not only rely on writing code. Multiple languages, architectures, and environments make the app development workflow complex and hard to maintain effectively and keep updated.

[Docker](https://www.docker.com/) helps to simplify and accelerate the development workflow, while offering the freedom to choose any tool and maintain different development environments for each project.

# Advantages of using Docker
There are a number of advantages to using a Docker container. Some of the important ones are listed below:

- If you upgrade to a new desktop or laptop (or want to use any of your friends' systems), you will have to manually download all the tools required in order to build Flutter apps. Docker really simplifies this process—there is no manual setup procedure. You can just grab the Dockerfile (along with some configurations) from your GitHub and run it on the system. Wait for the Docker container setup to complete, and now you have everything set up to get started building, testing, and debugging Flutter apps without any hassle.

- Forget the “it works on my machine” problem once and for all. Docker containers built using the same Dockerfile will have the exact same version of all tools available, no matter which server or system they are running on.

- Docker containers are very lightweight and portable because they do not have separate operating systems. This type of architecture is less resource-intensive, which makes it a better choice as compared to a virtual machine. Docker containers can start up very fast compared to virtual machines, and the resource usage varies depending on the load or traffic.

- Scaling up is also an easier task when using Docker containers than when using virtual machines, as there is no need to install an operating system in a Docker container. Unlike virtual machines, there is no need to allocate resources permanently to containers.

# What is a Docker Container?
A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries, and settings. This container image becomes a Docker container when it runs on the [Docker Engine](https://www.docker.com/products/container-runtime).
You can visit this [link](https://www.docker.com/resources/what-container) for more info about Docker Containers and how Containers are different from Virtual Machines (VMs).

