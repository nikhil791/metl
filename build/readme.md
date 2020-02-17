To create images locally:


Before building metl image place the metl.war file inside "build/metl/resources"

metl:
docker build -t metl:1.0  -f ./metl/metl.df metl

mysql:
docker build -t mysql:1.0 ./mysql




Once images are build locally, use docker-compose to run containers
docker-compose up ./docker-compose.yml
