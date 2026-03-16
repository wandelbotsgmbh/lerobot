# Docker image with mlflow integration


```bash
docker buildx build -f docker/Dockerfile.act --platform linux/amd64 --tag wandelbots.azurecr.io/developer-portal/lerobot-wabo:0.0.3 --push .
```