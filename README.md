Install Docker Engine
Update the apt package index:


 sudo apt-get update
Install Docker Engine, containerd, and Docker Compose.

Latest Version
To install the latest version, run:
 sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

Verify that the Docker Engine installation is successful by running the hello-world image.
 sudo docker run hello-world

This command downloads a test image and runs it in a container. When the container runs, it prints a confirmation message and exits.

You have now successfully installed and started Docker Engine.

Change Environtment  in docker-compose.yml file is recommended.

To run the Mautic Docker Application 
 docker-compose up -d
 
