# dokcer-laravel-handson

## 構築環境
- Docker 
- PHP8
- Laravel8
- Mysql8
- Nginx
- PhpMyAdmin

## Install & Start
`cd docker-laravel-handson`  
`docker compose up -d  --buildup `


### Container Login
`docker compose exec app bash`  
`docker compose exec db bash`  

### Laravel TopPage
[http:localhost:8080/](http:localhost:8080/)

### PhpMyAdmin  
[http:localhost:8081/](http:localhost:8081/)

## Git
remote ripository change  
`git remote set-url origin https://github.com/*******.git`

## tesmail server
.env 
```
MAIL_HOST=mail 
MAIL_PORT=1025 
MAIL_FROM_ADDRESS=info@example.com
```
