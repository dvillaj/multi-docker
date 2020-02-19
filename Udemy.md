# "Dockerizing" Multiple Services

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

## Starting up docker composer

```
docker-compose up --build
docker-compose up
``` 

# A Continuous Integration Workflow for Multiple Images


## Githut and Travis CI Setup

```
cd ~/projects/complex/
git init
git add .
git commit -m "initial commit"
``` 