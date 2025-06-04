# WEBD-3012 Business System Building and Testing Assignments
# Codin 1 Website

This project is a simple React web application running in a Docker container. It displays:

```html
<h1>Codin 1 website</h1>
```html

Here are the instructions on how to get the web application running on localhost:7775 (127.0.0.1:7775)
1.Clone the Repository. If you haven’t already, clone the repository:
  git clone <repository-url>
  cd <repository-directory>
2.Build the Docker Image. Run the following command to build the Docker image:
  docker build -t chen_zoey_coding_assignment11 .
This will build the Docker image using the Dockerfile provided.
3. Run the Docker Container. Run the container and map port 7775 to your local machine:
  docker run -it --rm -p 7775:7775 --name chen_zoey_coding_assignment11 chen_zoey_coding_assignment11
4. View the Web Application. Open your browser and navigate to:
  http://127.0.0.1:7775
You should see: Codin 1 website
