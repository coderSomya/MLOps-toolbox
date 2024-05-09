```
docker build -t lordocker:v1 .
```

```
docker run -dp 8081:5002 -ti --name lordocker lordocker:v1
```