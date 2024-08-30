# Build Docker Image
```
docker build -t demo-design-partern-image -f Dockerfile .
```

# Create container after build
```
docker create --name demo-design-partern demo-design-partern-image
```

# Run docker container
```
docker start demo-design-partern
```
```
docker stop demo-design-partern
```

```
docker attach demo-design-partern
```