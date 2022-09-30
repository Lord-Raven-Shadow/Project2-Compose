# Project2-Compose
Assessment 2 for Secure DevOps - ISEC 6000
Prepared by: 21153532 (Antony Villanueva)

## Summary
This repository contains the docker-compose.yml file which:

1. run a Docker-In-Docker (dind) container.
2. A Jenkins container which uses the dind container to run a Jenkin pipeline.

## HOW To Install

1. Fork the repository to your own repo.
2. Clone the repository - Click on code (green box), then click on HTTPS copy the link and in your terminal use the command - ```git clone <HTTPS url>```
3. Check if you meet the requirements to use the docker-compose.yml, the following requirements must be met.

a. Environment that supports it.
b. Latest Docker installed.
c. Latest Docker Compose installed.

References (Ubuntu): 			
[Install Docker](https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository)
[Post Install Steps](https://docs.docker.com/engine/install/linux-postinstall/)

4. If the requirements are met, open a terminal in your cloned github repository directory.
5. Use the follong command in a terminal, ```docker compose up```
6. Follow the propmts, in a browser, go to ```IP/ localhost>:8080``` and use the key in order to use Jenkins.
7. Follow the prompts in setting Jenkins up.


## How to Uninstall
1. To bring it all down use the command, ```docker compose down```
2. Use docker rm command to remove containers.
3. Delete unwanted files.


## Credits and references	

