# Node.js Docker Application

A simple Node.js web application with MongoDB database, containerized using Docker Compose.

## Components
- **Node.js App**: Express server serving web pages and handling user profiles
- **MongoDB**: Database for storing user data
- **Mongo Express**: Web-based MongoDB admin interface

## Quick Start

### Start the application:
```bash
docker-compose up -d
```

### Stop the application:
```bash
docker-compose down
```

### View logs:
```bash
docker-compose logs -f
```

### Rebuild and restart:
```bash
docker-compose up --build
```

## Access Points
- **Web App**: http://localhost:3000
- **Mongo Express**: http://localhost:8080
- **MongoDB**: localhost:27017

## Default Credentials
- MongoDB Username: `admin`
- MongoDB Password: `password`