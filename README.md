# project-dolibarr

#collaborators: Hamdi, Kaddour, Mohamed Amine, Samuel

- In order to run docker, you should first install it 

- The Makefile contains the commands in order to:

  - Build the Dolibarr image alone (without db) :
  
        make build
    
  - Execute the Dolibarr image alone (without db) :
  
        make run
        
- Docker-compose file contains the nessary tasks to run the images of dolibarr and Mariadb, you should execute it to run the containers :

        docker-compose up
  
- The files db-deployment.yaml, dolibarr-deployment.yaml, and dolibarr-service.yaml serve to be used with kubectl. You can generate them through using the docker-compose file and the Kompose (should be installed). 

- The .travis file should be used for the CI/CD part between git hub repository and travis CI. 
  
