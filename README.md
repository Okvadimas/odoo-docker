# Project Setup Guide

## Prerequisites
- Ensure you have **Docker** installed on your system.
- Ensure **Git** is installed.

## Setup Instructions

1. **Create a New Folder**
   ```sh
   mkdir project-folder && cd project-folder
   ```

2. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo-name.git .
   ```

3. **Build the Docker Containers** (This may take some time to download images)
   ```sh
   docker compose create
   ```

4. **Start the Containers**
   ```sh
   docker compose start
   ```

5. **Stopping and Removing Containers** (In case of errors or rebuild requirements)
   ```sh
   docker compose down
   ```
   After running this, repeat steps **3** and **4** to rebuild and restart the containers.

## Additional Notes
- To check running containers:
  ```sh
  docker ps
  ```
- To check logs:
  ```sh
  docker compose logs -f
  ```
- To restart the application:
  ```sh
  docker compose restart
  ```

For further troubleshooting, refer to the Docker documentation or open an issue in the repository (but for my lovely girl u can ask me directly 🥰).

