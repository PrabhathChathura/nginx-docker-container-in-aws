# Nginx Docker on AWS EC2 Project

## Overview
This project deploys a static "Coming Soon" website for **Moto Sensei** using an **NGINX Docker container** on an **AWS EC2** instance.

## Features
- **Static Webpage**: Displays a "Coming Soon" message along with Moto Sensei's branding.
- **Dockerized NGINX**: Runs the website inside a Docker container for portability.
- **AWS EC2 Hosting**: Ensures availability and scalability of the website.

## Prerequisites
- An AWS EC2 instance (Ubuntu recommended)
- Docker installed on the EC2 instance

## Setup Instructions

### 1. Connect to Your EC2 Instance
```sh
ssh -i your-key-name.pem ubuntu@your-ec2-public-ip
