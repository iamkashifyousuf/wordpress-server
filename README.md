# __WordPress with MySQL using Docker Compose__
### This repository contains a docker-compose.yml file to set up a WordPress site with a MySQL database. Using Docker Compose allows you to easily start and manage the services needed for running WordPress.
## __Overview__
### This setup involves two main services:
### 1. __MySQL Database:__ A MySQL 5.7 instance that stores WordPress data.
### 2. __WordPress:__ The latest WordPress instance, connected to the MySQL database.


## __Prerequisites__
### 1. Docker
### 2. Compose


## __Getting Started__
### 1. Clone the Repository
```
git clone https://github.com/iamkashifyousuf/wordpress-server.git
cd wordpress-server
```

### 2. Running the Services
```
docker-compose up -d
```


### 3. Accessing WordPress
### Open your web browser and navigate to http://localhost:8000. You should see the WordPress setup page. Follow the on-screen instructions to complete the setup.

### 4. Stop the Service and Delete Containers
### Press Ctrl + C
### To delete containers
```
docker-compose down
```


