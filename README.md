## End to end ML project using CICD 


## Run from terminal:
docker build -t testdockerkast.azurecr.io/application:latest .

docker login testdockerkast.azurecr.io

docker push testdockerkast.azurecr.io/application:latest