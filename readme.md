### mssql-mongo

使用 docker 部署 sql-server，用于开发测试，不建议生存环境使用。

### usage

```sh
git clone git@github.com:hectorqiu/mssql-docker.git

cd path/to/mssql-docker
docker-compose build
docker-compose start
```

### client 

##### CLI

```sh
pip install mssql-cli

mssql-cli -S localhost,1433 -U SA
```

##### GUI

- tablePlus
- navicat


