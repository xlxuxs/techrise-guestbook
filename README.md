# TechRise Guestbook

A simple guestbook web application where visitors can sign their name and leave a message. Built as a DevOps capstone project to demonstrate containerization, service orchestration, and CI/CD automation.

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Quick Start

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/techrise-guestbook.git
cd techrise-guestbook

# Copy environment variables
cp .env.example .env

# Start the application
docker compose up -d --build
