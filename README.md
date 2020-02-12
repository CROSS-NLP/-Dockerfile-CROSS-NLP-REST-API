# Deploy CROSS NLP REST API using Docker #


**1.** Open terminal, and clone the repository using:

	git clone https://github.com/CROSS-NLP/Dockerfile-CROSS-NLP-REST-API.git


**2.** Navigate inside of the directory and run the following command to build a image (this may take some time)

	docker build -t cross-nlp-rest-api .
  

**3.** To run the container enter the following command: 

	docker run -p <Port>:8080 -t cross-nlp-rest-api --name cross-nlp-rest-api

Replacing  `<Port>` with the port number you would like the container to be accessible on. For example if you want to access the container using via port `2097` then you would run :

	docker run -p 2097:8080 cross-nlp-rest-api --cross-nlp-rest-api


