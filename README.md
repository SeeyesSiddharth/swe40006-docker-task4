# SWE40006 Docker Task 4

Declared target level: Task 4.2 (Credit)

## flask-app (Task 4.2)
A basic Flask web app containerised with Docker, listening on port 5000.

Docker Hub image: css09/flask-app:1.0 (multi-platform: linux/amd64, linux/arm64)

Run it:
docker run -d -p 8080:5000 css09/flask-app:1.0

Then open http://localhost:8080
