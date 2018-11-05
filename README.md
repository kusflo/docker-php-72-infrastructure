	2 minutes ago
# Docker-php-72-infrastructure
Local infrastructure for the development of php 7.2 + mysql + nginx + network projects.

# Description
Configure a local container with docker without virtualizations and without messing up your equipment with the installation of programs.


# Requirements
Install docker and docker-compose in your system.


# Build infrastructure

```
cd infrastructure
docker-compose up -d --build
```

# Stop 

```
cd infrastructure
docker-compose stop
```

# Environment Variables
We can modify the environment variables in the .env file of infrastructure folder.
