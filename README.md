# php8-oci-docker
Docker-compose with PHP 8 &amp; OCI Extensions, Apache 2.4, Mailcatcher

## Apache
**Version:** 2.4.38

## PHP
**Version:** 8.1.0

**Extensions enabled:** OCI & MySQL
#### If you need more PHP extensions, change the `php-apache/Dockerfile` file and restart the containers

## Quick Start

#### Clone the repository:
`git clone https://github.com/eduarduhh/docker-php8.1`

#### Go to the root folder:
`cd php81-oci-docker`

#### Start the environment:
`docker-compose up -d`

#### Open your browser and go to:
`http://localhost:80`

#### SSH into the PHP & Apache container
`docker-compose exec php81 bash`

## Programs required
- Docker
- WSL2 
- **Enable WSL2 integration within Docker Desktop**
