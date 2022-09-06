# SQL Server Docker Compose


## Create file `sqlserver.env`

```
ACCEPT_EULA=Y
MSSQL_DATA_DIR=/var/opt/sqlserver/data
MSSQL_LOG_DIR=/var/opt/sqlserver/log
MSSQL_BACKUP_DIR=/var/opt/sqlserver/backup
```

## Create file `sqlserver.env`
```
MSSQL_SA_PASSWORD=Testing1122
```

## RUN `docker-compose`

```
docker-compose build
```

```
docker-compose up -d
```

## Finishing

```
docker-compose down
```

