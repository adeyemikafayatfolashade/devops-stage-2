# Full Stack Web Application Deployment

## Overview

This project contains a full stack web application with a React frontend and a FastAPI backend, deployed using Docker and Traefik.

## Requirements

- Docker
- Docker Compose
- Domain name (or subdomain)

## Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/adeyemikafayatfolashade/devops-stage-2.git

 ## Build and Run Docker Containers:
 sudo docker-compose up -d

 ## Access the Application:

 Frontend: http://twinmom.com
 Backend API: http://twinmom.com/api
 Backend Docs: http://twinmom.com/docs
 Backend Redoc: http://twinmom.com/redoc
 Adminer: http://db.twinmom.com
 Traefik Dashboard: http://proxy.twinmom.com

 ## Deployment
 Launch an EC2 Instance:
 Use an Ubuntu AMI.
 Allow traffic on ports 80 and 443.
 Install Docker and Docker Compose:
 sudo apt update
 sudo apt install docker.io
 sudo systemctl start docker
 sudo systemctl enable docker
 sudo apt install docker-compose

 ## Run the Repository:
 cd into the repository 
 sudo docker-compose up -d

 ## Links to the HNG Internship Program:
 https://hng.tech/internship
 https://hng.tech/hire
 https://hng.tech/premium

 ## License:
 This project is licensed under the MIT License - see the LICENSE.md file for details.
 
