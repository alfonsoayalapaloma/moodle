# moodle

Simple deployment of moodle using bitnami images.

Requires Docker. To install it:


#1. get the docker-compose file
curl -sSL https://raw.githubusercontent.com/bitnami/containers/main/bitnami/moodle/docker-compose.yml > docker-compose.yml

#2. get docker compose
curl -L https://github.com/docker/compose/releases/download/v2.21.0/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose


#3. run the composer
docker-compose up -d

#4. test server
http://localhost:80/


user: user
password: bitnami
