# Drupal Setup with Docker
This is a simple setup with docker-compose.yml

## Initial Setup
- Download docker https://www.docker.com
- Start Docker
- Download the version of Drupal that you are wanting to run
- Clone this repo
- Unzip Drupal download copy all files into repo
- Go to sites -> default and copy default.settings.php save copy as setting.php in same folder.

## For a New Site
- Open terminal and type `docker compose up`
- Open chosen browser and navigate to
  http://localhost:8033 and go through the Drupal setup.
- When inputting database info click on Advanced and change 
**Database host** to: `db:3306`