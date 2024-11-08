# Docker app

### Предпосылки
Контейнер создан на ubuntu-24-04-1.

### Образ докера
```shell
docker pull kussainovz/app_webapp_1
```
#### Полезные расположения файлов

* `/app` - Список специальных скриптов, веб-приложения и докерфайла
  
* `/app/prometheus` - отедельный каталог с prometheus.yml

### Для запуска введите в директории /app
```shell
docker-compose up -d --build
```
