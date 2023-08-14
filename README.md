# dockerize-chromadb
This GitHub repository showcases an example of running the Chroma DB Server in a Docker container, accessible to another service. Link to chromadb documentation: https://docs.trychroma.com/

In this repository I have provided an example where we run chromadb as a docker container. We create two containers. One container for the application that acts as a chroma client and one container for the chroma db server. You can find the 2 services in the docker-compose.yml file as 'application' and 'chroma'.

### Steps to make this work:
1. Clone the repository -> git clone https://github.com/abhitatachar2000/dockerize-chromadb.git
2. Move to the directory -> cd dockerize-chromadb
3. Create containers -> docker-compose up --build
