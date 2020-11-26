# LARAVEL, MYSQL, NGINX, PHP7.4 - Docker

## Setup

### Clone
```
git clone https://github.com/sambasallah/laravel-docker.git
```

### Start Docker Container
```
sudo docker-compose up -d
```

### Generate Laravel keys
```
sudo docker-compose exec app php artisan key:generate
```

### Stop Docker Container
```
sudo docker-compose down
```