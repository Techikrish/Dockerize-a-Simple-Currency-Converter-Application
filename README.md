## Prerequisites

- Docker installed on your machine. 
1. **Clone the repository**:

https://github.com/Techikrish/Dockerize-a-Simple-Currency-Converter-Application.git

2. **Build the Docker image**:

       docker build -t currency-converter

3. **Run the Docker container**:.

      
    docker run -p 5000:5000 currency-converter

    
5. **Access the application**:
Open your web browser and go to http://localhost:5000 to view the application.

### The Docker image for this application is available on Docker Hub:

 

    docker pull techikrish/currency-converter-application:1.0


### Running with Docker Hub Image

       docker run -d -p 5000:5000 --name currency-converter-app techikrish/currency-converter-application1.0
        
     


