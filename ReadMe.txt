docker run -itd -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123456 -p 5432:5432 -v /data:/mnt/PostgresSql/Data --name postgresql postgres
docker run --name pgadmin -p 82:82 -e 'PGADMIN_DEFAULT_EMAIL=user@domain.local' -e 'PGADMIN_DEFAULT_PASSWORD=postgresmaster' -d dpage/pgadmin4
