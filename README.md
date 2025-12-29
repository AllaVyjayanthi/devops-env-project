# DevOps Multi-Environment CI/CD Pipeline

This project demonstrates a DevOps workflow with three environments:
- Development (DEV)
- Testing (TEST)
- Production (PROD)

The application is containerized using Docker and deployed automatically using GitHub Actions.

## Project Structure

.github/workflows/   → CI/CD pipelines  
app/                 → Application source code  
.env.dev             → Development environment variables  
.env.test            → Testing environment variables  
.env.prod            → Production environment variables  
Dockerfile           → Docker build configuration  

## CI/CD Pipelines
- dev-deploy.yml → triggers on push to dev
- test-deploy.yml → triggers on push to test
- prod-deploy.yml → triggers on push to main

## Technologies Used
- Python
- Docker
- GitHub Actions

## Author
Alla Vyjayanthi
