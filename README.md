# wordpress-docker-multisite
How to host Wordpress multisite (path) using docker
3 files are required, docker-compose, and two apache configuration files

Create a folder on your docker server to host the two files
Use the docker compose file to setup Wordpress and MariaDB containers
Create some random passwords, and enable either ports or connect to your reverse proxy
Change the website address in the compose file
Set the paths for the source of the two files

I use this for internal websites for students, they sign up, I approve the user using https://en-gb.wordpress.org/plugins/unconfirmed/
