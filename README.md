# Disease Predictor

A web application for predicting diseases using machine learning algorithms.

## Project Structure

```
DISEASE_PREDICTIO/
├── Disease_predictor_backend/    # Backend FastAPI application
├── Studio_main/                  # Frontend application
└── Docker-compose.yml           # Docker composition file
```

## Prerequisites

- Docker(https://www.docker.com/products/docker-desktop/)
- Docker Compose
- Node.js (for local development)
- Python 3.9+ (for local development)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/USERNAME/disease-predictor.git
cd disease-predictor
```

2. Start the application using Docker Compose:
```bash
docker-compose up --build
```

3. Access the application:
- Frontend: http://localhost:5173
- Backend: http://localhost:8000

## Development

### Backend Development
The backend is built using:
- FastAPI
- Python 3.9+
- Machine Learning models

### Frontend Development
The frontend is built using:
- React
- TypeScript
- Vite
