# WordPress with MariaDB (2 containers)

This Docker Compose configuration sets up a WordPress instance connected to a MariaDB database.

## Usage

1. **Clone Repository:**
git clone <repository_url>

2. **Navigate to the Directory:**
cd <repository_directory>

3. **Start WordPress Stack:**
docker-compose up -d

4. **Access WordPress:**
- Open a web browser and go to `http://localhost:8080` to access WordPress.
- Follow the WordPress installation wizard using the database credentials provided in the `docker-compose.yml` file.

## Cleanup

To stop and remove the containers, run:
docker-compose down