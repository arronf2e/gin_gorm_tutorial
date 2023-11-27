### package used
- viper: load and validate the environment variables  
  go get github.com/spf13/viper
- gorm: connect to pgsql  
  go get -u gorm.io/gorm  
  go get gorm.io/driver/postgres
- uuid: generates and inspects UUIDs  
  go get github.com/google/uuid
- gin
  go get github.com/gin-gonic/gin
- air: livereload
  go get github.com/cosmtrek/air@latest


### Start pg docker container

```shell
docker-compose up -d
```

### migrate
```shell
go run migrate/migrate.go
```

### start server
```shell
air
```