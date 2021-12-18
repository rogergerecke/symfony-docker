# Symfony fast in Docker container

### This is my fast way to develop
Create a Docker container for Symfony and connect with the 


# Install

First in your IDE terminal

```
git clone https://github.com/rogergerecke/symfony-docker.git
git clone https://github.com/symfony/website-skeleton.git symfony
cd symfony
composer update

```

## Change in the docker-compose file
- add port to the database
```
ports:
  - "5432:5432"
```