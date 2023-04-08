Docker is an open source centralized platform designed to create deploy and run applications.

Docker uses the container on the host os to run applications.It allows applications to use the same Linux Kernal as asystem on the host computer,
rather than creating a whole new virtual os.
We can install docker on any os.
Docker is a tool that performs os-level virtualization,as known as containeraization.

Advantages:

Low cost,Budget friendly..
It can run on physical,virtual or on cloud.
It tooks very less time to create a container.

Docker contains:
Docker Daemon:
Docker deamon runs on the host o.s
It is responsible for running containers and managing docker service
One docker deamon can communicate with other docker deamon.

Docker client:

Docker users can interact with the docker deamon through a client.
Docker client uses commands and Rest api to communicate with the docker deamon.
when client runs any server commands on docker terminal the clint terminal sends the docker commands to the docker deamon.

DOcker Host:

Dockerhost is used to providing an environment to execute and run application.

Docker-Hub/Registry:
Docker Registry manages and store the docker images.

2 types of registries
1)private registry -->It is used for sharing images within enterprise.
2)public registry -->called as DockerHub

processes:

-->Take an image from DockerHub
-->create image from docker file
-->create an image from existing docker containers.

Docker container
The containter holds the entire package that needed to run the application.
the image is atemplete and the container is acopy of the template.
container is like virtualizationwhen they run on the docker engine.
images become containers when they run on the docker engine.


