# aur-devops

This repository aimed to deliver a pre-configured Jenkins server with jenkinsfile 'recipe', inside a docker container: built via docker-compose file, using a Dockerfile, and equipped with Python to interact with SCM and print an indication.


Main challenges:
1.	Orchestrating a pre-configured functioning Jenkins server for delivery
	-	Possible through jcasc file (here – jenkins.yaml)
4.	Enabling python script-running capabilities
	-	Possible through the Dockerfile 'recipe'.
5.	Intercepting merge trigger from SCM (GitHub)
	-	Possible through GitHub webhooks, and triggers.
