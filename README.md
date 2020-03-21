# Strapi quickstart docker environment

## Database 
- ./developmentDatabase contains a mysql database that strapi will connect to
- Database is stored at ./developmentDatabase/mysql

## Adminer
- Adminer runs on port 8080 (useful for exploring and debugging database)

## Strapi
- Your Strapi files live in `server` directory
- edit either the .env file or docker-compose.yml file to provide database env variables

# Getting started
- Change directory to Strapi server `cd server`
- run `docker-compose up`

and you're ready to go!
