# PHP + MySQLのDocker環境構築

## 環境
* PHP
* MySQL
* Nginx

## clone
```bash
git clone https://github.com/stepup-engineer/php-docker-project.git
cd php-docker-project
```

## コンテナ起動
```bash
cp .env.example .env
docker-compose up -d --build
```
