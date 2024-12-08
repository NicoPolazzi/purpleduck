# Network Security - Capture The Flag

Welcome to the Purple Duck Capture the Flag challenge!

Your goal is to find a flag with this structure: PURPLE_DUCK:{string}. If you find it, great job!

Hope you find the challenge fun and enjoy searching for the flag. 
Happy ducking 😁


## Installation and Running Guide

### Prerequisites

- Docker
- Docker Compose

### Steps to Install and Run

1. **Clone the repository and enter in**

   ```sh
   git clone https://github.com/NicoPolazzi/purpleduck.git
   cd purpleduck
   ```

2. **Start the application using Docker Compose**

    ```sh
    docker-compose up -d
    ```

    This will start the following services:
    - `duck-service` on port `8080`
    - `duck-db` on port `3306`
    
3. **Verify the services are running**

    For checking the status of the container, you can use:

    ```sh
    docker-compose ps
    ```

4. **Access the application**

    Just open your browser and go to http://localhost:8080 to get started with the challenge.

5. **Do not forget to stop the application**

    Before run, or when you're done with the app, don't forget to stop the app with:

    ```sh
    docker-compose down
    ```
