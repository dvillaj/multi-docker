# Complex

## Dockerizing a react application

```
cd complex/
cd client/
docker build -f Dockerfile.dev .
docker run ec82234b3a54
```

## Dockerizing generic Node Apps


```
cd complex/
cd server/
docker build -f Dockerfile.dev .

cd ../worker
docker build -f Dockerfile.dev .
```