# TP1_docker

Create a simple blog with Wordpress or Use an existing Wordpress Project.
Create a development environment for the project.

Obligations

Github Flow (PR mandatory)
Respect Github open source guidelines
Comment each line of the Dockerfile or docker-compose files
Complete README to initialize the project
Use only official Docker Hub images and lock versions of your images
Mandatory services :
	Wordpress (PHP & Apache/Nginx)
	Database
	phpMyAdmin
Push your image on Docker Hub or Github (follow the mandatory rules for each platform)

Bonus:
Create a prod environment for the project
Push your docker on a vps or on heroku
Services :
	Testing email service (MailHog)
	Proxy (Traefik)
	SSL certificat (Let's Encrypt) ⚠️ You need a domain name


# To get started :

- Open Cmd or Git Bash
- Use command git clone https://github.com/ThomasLB92/DockerPMNtp.git


# Run the project :

- In cmd, use command docker-compose up -d
- Open your browser and type :
		- http://localhost:8000/ to access Wordpress
		- http://localhost:8080/ to access Database


# Versions

wordpress:latest
mariadb:latest
phpmyadmin:latest

# Authors

- Alexis Fonteneau alias @qippa
- Thomas Le Bot alias @ThomasLB92

# License

This project is under MIT License