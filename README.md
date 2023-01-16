# jenkins-docker

This repo create to run jenkins as a container. 

you can run that repo like this on your local pc: 

# download repo
git clone https://github.com/smtarslanturk/jenkins-docker.git

# give permission to run script 
 sudo chmod +x -R jenkins-docker/  

# change directory to jenkins files 
cd jenkins-docker/

# create docker network named jenkins
./1-jenkins-network.sh

# Creating a docker image thanks to dockerfile
./2-buildDockerfile.sh

# run docker dind container 
./3-runDockerDind.sh

# run jenkins as a container 
4-runDockerJenkins.sh