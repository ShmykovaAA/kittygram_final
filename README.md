# Kittygram

Kittygram is a full-stack web application for sharing information about cats, their achievements, and photos.

The project demonstrates containerized deployment, CI/CD automation, backend API development, and production configuration with Nginx and Docker Compose.

## Features

- User registration and authentication
- Create, edit, and delete cat profiles
- Upload cat photos
- Add achievements to cat profiles
- REST API for frontend-backend communication
- Containerized application environment
- Automated testing and deployment with GitHub Actions
- Production deployment with Nginx and Docker Compose

## Tech Stack

### Backend
- Python
- Django
- Django REST Framework
- Gunicorn

### Frontend
- JavaScript
- React

### Infrastructure
- Docker
- Docker Compose
- Nginx
- GitHub Actions
- CI/CD

### Testing
- Pytest

## Project Structure

```text
kittygram_final/
├── backend/        # Django backend and REST API
├── frontend/       # React frontend
├── nginx/          # Nginx configuration
├── tests/          # Automated tests
├── .github/
│   └── workflows/  # CI/CD workflows
├── docker-compose.yml
├── docker-compose.production.yml
└── .env.example
