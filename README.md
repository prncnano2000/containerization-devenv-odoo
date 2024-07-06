

|| [Prerequisites](#prerequisites) ||
[Deployment](#deployment) ||
[Authors](#authors) ||

# containerization-devenv-odoo

This project uses Docker Compose to create and manage a local environment consisting of two containers `eazy-odoo-15` and `eazy-db-15` generating based on images `odoo:15` and `postgres:15` then provided a bash script to manage the application.
## Technologies

**Docker :** `Docker compose`


## Features


- Creates Docker containers and links them using a Docker feature called `docker compose`
- A bash script which allows you to choose the action to be done on the application launched by our docker compose which will be the `build`, the `launch` or the `deletion` of the application.
## Prerequisites

- **Docker:** install docker on your machine on Windows by following the link https://docs.docker.com/desktop/install/windows-install/ and on a Linux system follow https://docs.docker.com/desktop/install/linux-install/.

Once Docker is installed, you can start using it to run Docker images and containers. You can find more information about using Docker on the Docker website: https://docs.docker.com/.


## Installation


\
In your command prompt download the repo with the commands:
```bash
  git clone https://github.com/AnselmeG300/containerization-devenv-odoo.git

  cd containerization-devenv-odoo

  code . 
```

    
## Deployment

\
As everyone said, the bash script will allow you to perform a set of batch actions, including:

1- `build_start`: Allows us to update our code from our repository (pull) then allows us to launch our application (start) and finally allows us to view the logs of our running application (tail).

2- `start`: allows us to launch our application (start) then allows us to view the logs of our running application (tail).

3- `stop`: Allows us to stop our application (down)

4- `purge`: Allows us to stop our application (down) then allows us to delete our volumes (delete)

To do this, you will need to write in your terminal:

- Make our script executable with
```bash
 chmod +x run.sh
```
- Launch our script with
```bash
 ./run.sh
```
## Authors

- [@AnselmeG300](https://github.com/AnselmeG300/terraform-cloud.git)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

