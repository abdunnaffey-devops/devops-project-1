cat > README.md << 'EOF'
# DevOps Project 1 — CI/CD Pipeline

## What this project does
Every time code is pushed to GitHub, a GitHub Actions pipeline automatically builds a Docker image and pushes it to Docker Hub.

## Tools used
- Docker
- GitHub Actions
- Docker Hub

## Pipeline flow
Code pushed to GitHub → GitHub Actions triggered → Docker image built → Pushed to Docker Hub

## How to run locally
docker pull abdunnaffey/devops-project-1:latest
docker run -d -p 8080:80 abdunnaffey/devops-project-1:latest

Then open http://localhost:8080 in your browser
EOF
