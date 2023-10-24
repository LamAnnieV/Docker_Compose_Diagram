# Docker_Compose_Diagram

# Docker_Compose_Diagram

October 24, 2023

By:  Annie V Lam - Kura Labs

## Diagram

![image](docker_diagram.drawio.png)

## Is Dockerfiles and Docker Compose declarative or imperative?

Dockerfiles is imperative, the execution of the instructions in the dockerfile in the order as it appears 

Docker Compose is delcarative.  The order of services listedin the docker-compose.yml file is not important, what is important is if there is a "depends_on:" clause.   If there is no "depends_on:" clause in the file, then the order of containers created is not important.  However, if there is a "depends_one" clause, then the continer that service block depends on needs to be created first.  
