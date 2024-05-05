# Docker Compose Scripts Repository

This repository contains Docker Compose YAML files for setting up various services and applications in Docker containers. Each script represents a specific setup scenario, making it easy to deploy and manage Dockerized environments for different purposes.

## Directory Structure

- **`wordpress_mariadb/`**: Docker Compose script for WordPress with MariaDB (2 containers).
- **`nextcloud_mariadb/`**: Docker Compose script for Nextcloud with MariaDB (2 containers).
- **`uptime_kuma_mongodb/`**: Docker Compose script for Uptime Kuma with MongoDB (1 container).
- **`mariadb_phpmyadmin/`**: Docker Compose script for MariaDB with phpMyAdmin (1 container).
- **`postgresql & pgadmin/`**: Docker Compose script for postgres with pgAdmin (1 container).
- **`Gitea/`**: Docker Compose script for Gitea with postgresql (1 container).

## Usage

1. **Clone Repository:**

2. **Navigate to the Directory:**
cd <repository_directory>

3. **Choose a Script:**
- Navigate to the directory corresponding to the desired Docker Compose script.

4. **Start Docker Stack:**
docker-compose up -d

5. **Access the Service:**
- Follow the instructions provided in the corresponding README file within the directory to access and configure the service.

## Contributions

Contributions to this repository are welcome! If you have additional Docker Compose scripts to share or improvements to existing ones, feel free to submit a pull request.

## License

This repository is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the contents of this repository for any purpose.

