# conversao-distancia
You have two options to run this project, build the image or just pull it from DockerHub


# Clone the repository and build the image
You can clone this repository and use the Dockerfile to build the image using the command:<br><br>
<code>git clone https://github.com/walterti/conversao-distancia.git</code><br>
<code>docker build -t conversao-distancia</code>

and run the container using the command:

<code>docker container run -d -p 5000:5000 conversao-distancia</code>

# Pull image from DockerHub
You can instead just pull the image from DockerHub using:

<code>docker pull walterti/conversao-distancia</code>

Run the container using:

<code>docker container run -d -p 5000:5000 walterti/conversao-distancia</code>

# Access the running app
Access http://localhost:5000 on your local machine browser
