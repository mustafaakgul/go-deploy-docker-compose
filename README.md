
docker build -t loadbalance-api .
docker run --name api --rm -p 5000:5000 loadbalance-api

After docker compose
docker-compose up --build