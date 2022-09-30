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
	
	- **Requirements:**
		- Environment that supports it.
		- Latest Docker installed.
		- Latest Docker Compose installed.

	- **References (Ubuntu):** 			
		- [Install Docker](https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository)
		- [Post Install Steps](https://docs.docker.com/engine/install/linux-postinstall/)

4. If the requirements are met, open a terminal in your cloned github repository directory.
5. Use the follong command in a terminal, ```docker compose up```
6. Follow the propmts, in a browser, go to ```IP/ localhost>:8080``` and use the key in order to use Jenkins.
7. Follow the prompts in setting Jenkins up.


## How to Uninstall
1. To bring it all down use the command, ```docker compose down```
2. Use ```docker rm <container ID> ``` *(to stop use ```docker stop <container ID>```)* and similar commands to remove/ stop containers.
3. Delete unwanted files.


## Credits and references	

This assignment was made possible by referring to the following references for inspiration, code adaption, guidance, troubleshooting, and learning how to do things I want to implement for the assignment.

- "Deploying a Docker Container on Ec2." 2022, accessed 28 September 2022, 2022, https://awstip.com/deploying-a-docker-container-on-ec2-43da46ef3007.
- Architect, e2e Solution. "Install Docker in Ec2 on Ubuntu Image." YouTube, 29 September 2022 2020. https://www.youtube.com/watch?v=ftAWCI_z1Lg&ab_channel=e2eSolutionArchitect.
- "Docker: Driver Failed Programming External Connectivity on Endpoint Webserver." 2016, accessed 30 September 2022, 2022.
- "Docker-Compose 1.28.0 Fails on Ubuntu 18.04: "Version `Glibc_2.28' Not Found" #8048." 2021, accessed 29 September 2022, 2022, https://github.com/docker/compose/issues/8048.
- CloudBeesTV. "How to Use Docker Compose with Jenkins." YouTube, 29 September 2022 2022. https://www.youtube.com/watch?v=ZPD_PzGOvFM&ab_channel=CloudBeesTV.
- Coach, DevOps. YouTube, 29 September 2022 2022. https://www.youtube.com/watch?v=OSJr-BMg2YQ&ab_channel=DevOpsCoach.
- Dane, Mike. "Yaml | in One Video." YouTube, 29 September 2022 2017. https://www.youtube.com/watch?v=cdLNKUoMc6c&ab_channel=MikeDane.
- "Jenkins-Example-Docker/Jenkinsfile-1." 2021, accessed 28 September 2022, 2022, https://github.com/darinpope/jenkins-example-docker/blob/main/Jenkinsfile-1.
- "Run Jenkins in Docker Using Docker Compose with Persistent Volumes." Digital Avenue, 2021, accessed 29 September 2022, 2022, https://digitalavenue.dev/Run-Jenkins-On-Docker-Compose/.
- "Get Started with Docker Compose." accessed 29 September 2022, https://docs.docker.com/compose/gettingstarted/.
- "Basic Writing and Formatting Syntax." 2022, accessed 30 September 2022, 2022, https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax.
- Han, Tiu Wee, "Docker in Jenkins in Docker," 28 September 2022, 2020, https://www.tiuweehan.com/blog/2020-09-10-docker-in-jenkins-in-docker/.
- "How to Use Git Commands from Linux Terminal." Unixmen, 30 September 2022, https://www.unixmen.com/use-git-commands-linux-terminal/.
- ISEC6000. "Lab 02." ISEC6000 SecureDevOps, Semester 2, 2022.
- ———. "Lab 06." ISEC6000 SecureDevOps, Semester 2, 2022.
- "Build a Node.Js and React App with Npm." accessed 28 September 2022, https://www.jenkins.io/doc/tutorials/build-a-node-js-and-react-app-with-npm/https://www.jenkins.io/doc/pipeline/tour/hello-world/.
- "Creating Your First Pipeline." accessed 28 September 2022, https://www.jenkins.io/doc/pipeline/tour/hello-world/.
- "Pipeline Syntax ", accessed 28 September 2022, https://www.jenkins.io/doc/book/pipeline/syntax/.
- "Using Docker with Pipeline." accessed 28 September 2022, https://www.jenkins.io/doc/book/pipeline/docker/.
- "How to Name or Rename Docker Containers." Tecmint: Linux Howtos, Tutorials & Guides, 2018, accessed 30 September 2022, https://www.tecmint.com/name-docker-containers/#:~:text=How%20to%20Name%20a%20Docker,print%20the%20new%20container%20ID.
- "Docker: Not Found in Jenkins Pipeline." 2017, accessed 29 September 2022, 2022, https://forums.docker.com/t/docker-not-found-in-jenkins-pipeline/31683?page=2.
- "[Solved] Getting `Glibc_2.32′ and `Glibc_2.34′ Not Found in Jenkins (Docker) with Dind on Ubuntu 22.04." 2022, accessed 29 September 2022, 2022, https://jtuto.com/getting-glibc_2-32-and-glibc_2-34-not-found-in-jenkins-docker-with-dind-on-ubuntu-22-04/.
- McKenzie, Cameron, "Fix the Jenkins Error: Invalid Agent Type Docker Specified [Any, Label, None]." TheServerSide, 2020, https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Fix-Jenkins-Invalid-agent-type-- Docker-specified-any-label-none-error.
- "Troubleshooting Jenkins Pipeline Failure Issues." 2022, accessed 28 September 2022, 2022, https://docs.bmc.com/docs/brid213/troubleshooting-jenkins-pipeline-failure-issues-1056381771.html.
- Solutions, Android and Tech. "How to Install Jenkins in Aws Ec2 Ubuntu Instance." YouTube, 29 September 2022 2019. https://www.youtube.com/watch?v=8s71mIOpOAI&t=240s&ab_channel=AndroidandTechSolutions.
- Step, Automation Step by. "Jenkinsfile Beginner Tutorial 1 | What Is Jenkinsfile | How to Create Jenkinsfile | Step by Step." YouTube, 29 September 2022 2021. https://www.youtube.com/watch?v=RsD2nzPY0is&ab_channel=AutomationStepbyStep.



