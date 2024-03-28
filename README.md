# Execute the following commands to Dockerize the Dash application

docker build -t Dash_maps .
docker run -h localhost -p 9002:9000 -d --name Dash_maps Dash_maps
