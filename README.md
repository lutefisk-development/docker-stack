# Docker commands:   
   
To start your docker containers in development:   
`docker compose -f docker-compose.dev.yaml up --build -d`   

To start your docker containers in production:   
`docker compose up --build -d`

To shut down your docker containers:   
`docker compose down`    

To see which containers are running:   
`docker ps`    

To see which services are running:   
`docker compose ps`    
   
To install packages locally:   
```
cd app
composer install --ignore-platform-reqs
```     