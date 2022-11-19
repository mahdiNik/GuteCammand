docker run -itd -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123456 -p 5432:5432 -v /data:/mnt/PostgresSql/Data --name postgresql postgres
