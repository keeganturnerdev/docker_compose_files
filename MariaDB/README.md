# MariaDB with phpMyAdmin (1 container)

This Docker Compose configuration sets up a MariaDB database with phpMyAdmin for database management.

## Usage

1. **Clone Repository:**
git clone <repository_url>

2. **Navigate to the Directory:**
cd <repository_directory>

3. **Start MariaDB with phpMyAdmin Stack:**
docker-compose up -d


4. **Access phpMyAdmin:**
- Open a web browser and go to `http://localhost:8080` to access phpMyAdmin.
- Log in with the MySQL root credentials provided in the `docker-compose.yml` file.

## Cleanup

To stop and remove the containers, run:
docker-compose down