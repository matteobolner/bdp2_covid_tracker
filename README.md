# bdp2_covid_tracker
Repository for the hands-on on covid-19 data using docker and jupyter notebooks

An application stack consisting of a jupyter notebook retrieving COVID-19 data from the Protezione Civile department's GitHub repo, and Portainer to monitor it. The jupyter notebook container is enabled for https access.

DockerHub repo:
https://hub.docker.com/repository/docker/matteobolner/bdp2_covid_tracker  

Repository structure:  
**docker_command.txt** --> contains an obsolete command, used in the beginning to build locally a single jupyter notebook image  
**docker-compose.yml** --> used by docker-compose to build the application stack  
**.docker** --> contains the Dockerfile used to build the image available on DockerHub, based on the official Jupyter notebook minimal image  
**.work** --> contains the actual Jupyter notebook for the data analysis
