# Node-Docker-Express-Postgres-SequalizeORM
```
docker-compose up
```
To rebuild this image
```
docker-compose up --build
```
Recreate build
```
docker-compose -f docker-compose.yml up --build --force-recreate

docker-compose run userdirectory npm run migrate
```
Remove images
```
docker-compose rm
```
