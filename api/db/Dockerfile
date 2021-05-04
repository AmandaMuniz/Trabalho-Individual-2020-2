from postgres:13.2-alpine

WORKDIR /db

COPY initialDB.sql /docker-entrypoint-initialDB.d/

COPY . .