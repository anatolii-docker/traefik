# traefik
Запуск проекта: команда sudo docker-compose up -d

Добавление нового контейнера: 
 - скопируйте блок кода  для запуска nginx;
 - замените имя сервиса, контейнера, название роутеров (traefik.http.routers.NGINX.entrypoints=websecure");
 - в volumes смонтируйте свой сайт;
 - в Host(`site.fedorov.parseq.pro`) - вставте название своего домена.
 
Перазапуск проекта: sudo docker-compose down && sudo docker-compose up -d
