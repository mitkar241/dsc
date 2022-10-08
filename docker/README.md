# Containerization
---

## Containers
---
Containers are a form of lightweight virtualization that help in providing isolation among processes. Containers are heavier than a chroot but lighter than a hypervisor.

## Alpine and why we need it
---

# Docker
---

- [ ] [Top Docker Interview Questions and Answers - intellipaat](https://intellipaat.com/blog/interview-question/docker-interview-questions-answers/)
- [ ] [Top 50 Docker Interview Questions You Must Prepare In 2022 - edureka](https://www.edureka.co/blog/interview-questions/docker-interview-questions/)

## What is Docker?
---
| Criteria | Docker | Virtual Machines |
| --- | --- | --- |
| Use of OS | All containers share the host OS | Each VM runs on its own OS |
| Startup time | Very fast | Slow |
| Isolation | Process-level isolation | Full isolation |
| Security | Low | High |

We can define Docker as a containerization platform that combines all our applications in a package so that we have all the dependencies to run our applications in any environment. This means, our application will run seamlessly on any environment, and this makes it easy for having a product-ready application. What Docker does is wrap the software needed in a file system that has everything for running the code, providing the runtime and all the necessary libraries and system tools. Containerization technology like Docker will share the same operating system kernel with the machine, and due to this it is extremely fast. This means that we have to run Docker only at the beginning and after that, since our OS is already running, we will have a smooth and seamless process.

## Define Containerization.
---
Containerization is a form of virtualization through which applications are run in containers (isolated user spaces) all using a shared OS. It packs or encapsulates software code and all its dependencies for it to run in a consistent and uniform manner on any infrastructure.

## What is the benefit of using a Docker over a Hypervisor?
---
Though Docker and Hypervisor might do the same job overall, there are many differences between them in terms of how they work. Docker can be thought of as lightweight since it uses very few resources and also the host kernel rather than creating it like a Hypervisor.

## What are the unique features of Docker over other containerization technologies?
---
Some of the most important and unique features of Docker are as follows:
- We can run our Docker container either on our PC or on our enterprise IT system.
- Along with the Docker Hub, which is a repository of all containers, we can deploy and download all our applications from a central location.
- We can even share our applications with the containers that we create.

## What is a Docker image?
---
A Docker image helps in creating Docker containers. We can create the Docker image with the build command; due to this, it creates a container that starts when it begins to run. All the Docker images are stored in the Docker registry such as the public Docker registry. These have minimal amounts of layers within the image so that there is a minimum amount of data on the network.

## What is a Docker container?
---
It is a comprehensive set of applications including all its dependencies which share the same OS kernel, along with the other containers running in separate processes within the operating system in a user space. Docker is not tied to any IT infrastructure, and thus it can run on any computer system or on the cloud. We can create a Docker container using Docker images and then run it, or we can use the images that are already created in the Docker Hub. To simplify things, let’s say that the Docker containers are just runtime instances of the Docker image.

## What is a Docker Hub?
---
We can think of Docker Hub as a cloud registry that lets us link the code repositories, create the images, and test them. We can also store our pushed images, or we can link to the Docker Cloud, so that the images can be deployed to the host. We have a centralized container image discovery resource that can be used for the collaboration of our teams, automating the workflow and distribution, and changing management by creating the development pipeline.

## What is a Docker Swarm?
---
We can think of a Docker Swarm as the way of orchestrating the Docker containers. We will be able to implement Dockers in a cluster. We can convert our Docker pools into a single Docker Swarm for easy management and monitoring.

## What is the use of a Dockerfile?
---
A Dockerfile is a set of specific instructions that we need to pass on to Docker so that the images can be built. We can think of the Dockerfile as a text document which has all the commands that are needed for creating a Docker image. We can create an automated build that lets us execute multiple command lines one after the other.

## What is Docker Compose?
---
Docker Compose defines and runs multi-container Docker applications. With Compose, a YAML file is used to configure an application’s services. All the services from the configuration can be created and started with a single command.

## Why use Docker?
---
Following are the reasons why one should use Docker:
- It allows the use of system resources more efficiently
- Software delivery cycles are faster with it
- Application portability is possible and easy
- It is great for the microservices architecture

## What are the drawbacks of Docker?
---
Docker has a few drawbacks as listed below:
- No storage option
- Poor monitoring 
- Unable to automatically reschedule inactive nodes
- Has a complicated automatic horizontal scaling setup

## What is Docker Engine?
---
Docker Engine is an open-source containerization technology that facilitates the development, assembling, shipping, and running of applications with the help of the following components:
- Docker Daemon
- Docker Engine REST API
- Docker CLI

## What are registries?
---
Docker registries provide locations for storing and downloading images. There are two types of registries
- Public registry
- Private registry
Public registries include Docker Hub and Docker Cloud.

## What are Docker namespaces?
---
When a container is run, Docker creates a set of isolated workspaces for the container called namespaces. 

## How to use Docker?
---
The Docker command syntax looks like this:
```
docker run [OPTIONS] IMAGE [COMMAND] [ARG...]
```
To run a container, we must incorporate the image on which it is based:
```
docker run [docker_image]
```
We can run containers if the Docker images are locally stored. If they are not, the software will take it from the online registry.

Docker can be used to run a container:

- Under a specific name
- Interactively
- And publish container ports
- In the background in the detached mode
- And mount host volumes
- And remove it once the process is complete

## Is it possible to use JSON instead of YAML for Docker Compose?
---
We can use JSON instead of YAML for a Docker Compose file. When we are using the JSON file for composing, we have to specify the filename with the following command:
```
docker-compose -f docker-compose.json up
```

## What is the process for creating a Docker container?
---
We can use any specific Docker image for creating a Docker container using the below command:
```
docker run -t -i command name
```
This command not only creates the container but also starts it for us. If we want to check whether the Docker container has been created or not, then we need to have the following command that will list all the Docker containers, along with the host on which the Docker containers run:
```
docker ps -a
```

## What is the process for stopping and restarting a Docker container?
---
To stop a Docker container, we need to use the following command:
```
docker stop CONTAINER_ID
```
To restart a Docker container, we need to use the following command:
```
docker restart CONTAINER_ID
```

## How to create a Docker image?
---
A Docker image can be built using the following command:
```
$ docker build .
```

## How to stop a Docker container?
---
We can use the following to stop one or more running Docker containers:
```
docker container stop [OPTIONS] CONTAINER [CONTAINER...]
```

## How to remove Docker images?
---
Use docker images with the -a flag to get the image IDs for removal. Then, pass their IDs or tags to
```
docker rmi
```
List:
```
docker images -a
```
Remove:
```
docker rmi Image Image
```

## Where are Docker images stored?
---
It depends on which system the Docker is running and the Docker storage driver is being used.

For example, on Windows, Docker images are stored by default in:
```
C:\ProgramData\DockerDesktop
```
On a Mac, Docker images are stored by default in:
```
~/Library/Containers/com.docker.docker/Data/vms/0/
```

## How to run a Docker image?
---
The ‘docker run’ command runs an image inside the container. It will require the image name. 
```
docker run [docker_image]
```

## How to start a Docker container?
---
The following command starts a Docker container:
```
docker container start [OPTIONS] CONTAINER [CONTAINER...]
```

## How to use Docker Compose?
---
Docker Compose typically includes a three-step process:
- Using a dockerfile to define the app’s environment to facilitate reproduction anywhere
- Defining the app services in docker-compose.yml so that they can run in an isolated environment together
- Running docker-compose up

## What command should be run to view all the running Docker containers?
---
To view all the running containers in Docker, we can use the following:
```
$ docker ps
```

## What is Docker daemon?
---
Docker daemon is a service that manages Docker containers, images, storage volumes, and the network. It constantly listens to Docker API requests and processes them. A daemon can communicate with other daemons as well for the management of Docker services.

## Name and explain the states of a Docker container.
---
- Created: We see this Docker container state when a container is newly created.
- Restarting: When the Docker container is restarted due to any issues, this state is observed.
- Running: It is the main state for the container after it has started.
- Paused: When a running Docker container is temporarily stopped via docker pause, this is the status that we will see.
- Exited: If a container has stopped due to some issue or stopped manually, this will be the state of the container.
- Dead: When the daemon has tried but failed to stop a container (mostly because of a busy device or resource), this state will be seen.

## What is Docker Hub?
---
Docker Hub helps with linking to code repositories. This cloud-based registry enables the building, testing, and storing of images in Docker Cloud. Images can also be deployed to the host with it.

## Define Virtualization.
---
Virtualization is the process of logically dividing mainframes to enable more than one application to run at a time.

## What is a Hypervisor?
---
A hypervisor helps in the creation of a virtual environment, in which the guest virtual machines run. It manages the guest systems and checks the required resource allocations to the guests.

## What are Docker object labels?
---
Docker object labels help us add metadata to Docker objects, including containers, images, Swarm nodes, network, volumes, and services.

## What are the steps in a Docker container life cycle?
---
- Build
- Pull
- Run

## Name the three components of the Docker architecture.
---
- Client
- Docker host
- Registry

## How do you scale your Docker containers?
---
Docker containers can be scaled to any level, starting from a few hundreds to even thousands or millions of containers. The only condition is that the containers need the memory and the OS all the time, and there should not be a constraint on these when the Docker is getting scaled.

## How does communication happen between Docker client and Docker daemon?
---
The communication between Docker client and Docker daemon happens with the help of the combination of TCP, Rest API, and Socket.IO.

## Explain the implementation method of continuous integration (CI) and continuous deployment (CD) in Docker.
---
- Run Jenkins on Docker
- Using docker-compose, run integration tests in Jenkins

## How to run a Docker container?
---
The Docker run command manages the running of containers in Docker. 

#### Running a container under a specific name:

The command for running a container under a specific name is:
```
docker container run --name [container_name] [docker_image]
```

#### Running a container in the background in the detached mode:

The command for running a container in the background is:
```
docker container run -d [docker_image]
```

#### Running a container interactively:

The following command is run for running a container interactively:
```
docker container run -it [docker_image] /bin/bash
```

#### Running a container and publishing container ports:

We have to include -p to the docker run command, along with the following:
```
-p [host_ip]:[host_port]:[container_port]
```
Here, host_ip is optional. It is not mandatory to specify this while we run the command.

#### Running a container and mounting host volumes:

The docker container run command looks like this:
```
docker container run -v [/host/volume/location]:[/container/storage] [docker_image]
```

## Tell us how you have used Docker in your past position.
---
This is a question wherein we could bring upon our whole experience with Docker and any other Container technologies we have used prior to Docker. We could also explain the ease that this technology has brought in the automation of the development-to-production life cycle management. We can also discuss any other integrations that we might have worked, along with Docker, such as Puppet, Chef, or even the most popular of all technologies—Jenkins. If we do not have any experience with Docker but we have it with similar tools from this space, we could convey the same and also show our interest in learning this leading containerization technology.

## Docker need
---

## Docker CLI to show all containers
---

## delete image with container
---

## delete all old unused images
---

## reduce docker images
---

## docker image storage location
---
