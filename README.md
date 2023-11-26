### package used
- viper: load and validate the environment variables  
  go get github.com/spf13/viper
- gorm: connect to pgsql  
  go get -u gorm.io/gorm  
  go get gorm.io/driver/postgres


### Start pg docker container

```shell
docker-compose up -d
```