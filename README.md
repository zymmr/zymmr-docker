# zymmr-docker

**Note:** This setup is not recommended for production use. For production setups, please contact support@ziyanasoftware.com.

## Windows

1. **Install Docker Desktop:** If you haven't already, you need to install Docker Desktop on your Windows machine. Docker Desktop provides an easy-to-use interface for managing Docker containers and images on Windows. You can download it from the official Docker website and follow the installation instructions.

2. **Clone this repo or download the compose file:** This file will define the configuration for your Docker containers, including the environment variables, services, networks, and volumes.

3. **Open Command Prompt or PowerShell:** Open Command Prompt or PowerShell on your Windows machine.

4. **Navigate to Project Directory:** Use the `cd` command to navigate to the directory where your `docker-compose.yml` file is located.

5. **Run Docker Compose Command:** Once you're in the correct directory, you can run the following command to start the containers defined in your `docker-compose.yml` file:
    ```bash
    set SITE_NAME=abc.zymmr.com && docker-compose up -d
    ```
    This command sets the `SITE_NAME` environment variable to `abc.zymmr.com` and then starts the Docker containers defined in the `docker-compose.yml` file in detached mode (`-d` flag).

6. Once the containers are up and running, you can verify that everything is working as expected. You can access your website by opening a web browser and navigating to `http://<server-ip>.zymmr.com` if you've configured DNS or hosts file accordingly.


## Linux

1. **Install Docker Engine:** If you haven't already, you need to install Docker Engine on your Linux machine. Docker Engine provides a platform to develop, ship, and run containers. You can install it by following the official Docker documentation for your specific Linux distribution.

2. **Clone this repo or download the compose file:** This file will define the configuration for your Docker containers, including the environment variables, services, networks, and volumes.

3. **Open Terminal:** Open a terminal on your Linux machine.

4. **Navigate to Project Directory:** Use the `cd` command to navigate to the directory where your `docker-compose.yml` file is located.

5. **Run Docker Compose Command:** Once you're in the correct directory, you can run the following command to start the containers defined in your `docker-compose.yml` file:
    ```bash
    SITE_NAME=abc.zymmr.com && docker-compose up -d
    ```
    This command sets the `SITE_NAME` environment variable to `abc.zymmr.com` and then starts the Docker containers defined in the `docker-compose.yml` file in detached mode (`-d` flag).

6. Once the containers are up and running, you can verify that everything is working as expected. You can access your website by opening a web browser and navigating to `http://<server-ip>.zymmr.com` if you've configured DNS or hosts file accordingly.
