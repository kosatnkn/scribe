[< Back](./../README.md)

# MariaDB

### Create volume
```bash
	docker volume create mariadb_data
```

### Install
```bash
	docker run -d -p 3306:3306 --name mariadb -v mariadb_data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=root mariadb
```
