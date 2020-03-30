# Deploy Your First Docker Container
### before you do anything Docker related you have to have docker decktop downloaded and running (requires a docker account)
- Link to download: https://www.docker.com/products/docker-desktop

## Step 1: Find the Docker Image of the Container 
- A Docker Image is a "snapshot" of the Docker Virtual machine at specific point in the process that includes everything needed to run the container
- the Image is used to search for Docker Containers 
- Find the docker Image you want either from  registry.hub.docker.com/ or via command: search docker <name>

## Step 2: Run the container
- command to run a container: docker run -d <name>
- this command will also automatically pull the latest version of the image if you dont have it installed already
-  And you're done :)..... if you don't want to access the container 

## Step 3: Accessing the Container
- In order to access the container you need to expose the port that its running on
- After running







### Sources:
- https://stackify.com/docker-image-vs-container-everything-you-need-to-know/
- https://docs.docker.com/get-started/ 
