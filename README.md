# KEYCLOAK DOCKER

Use KeyCloak docker with your local database.

## Configuration

Create .env file with the following content and replace XXXXXXXXXXXX with the correct information :
```env
KC_DB_USERNAME=XXXXXXXXXXXX
KC_DB_PASSWORD=XXXXXXXXXXXX
KC_HOSTNAME=XXXXXXXXXXXX
KC_HOSTNAME_PORT=XXXXXXXXXXXX
KEYCLOAK_ADMIN=XXXXXXXXXXXX
KEYCLOAK_ADMIN_PASSWORD=XXXXXXXXXXXX
DB_NAME=XXXXXXXXXXXX
```

## Execute
```sh
$ docker-compose up
```
