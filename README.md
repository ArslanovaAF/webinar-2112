# webinar-2112
docker pull <image> - скачать образ
docker push <image> - отправить образ в docker hub
docker run <image> - запустить образ
docker run -it <image> - запустить образ в интерактивном режиме (чтобы можно было отправлять в него команды)
docker run -p 3001:3001 <image> - запустить образ, опубликовав его на 3001 порту
docker system prune -f - очистить БД докера (-fa чтобы вычистить все, что не запущено)
docker ps - посмотреть запущенные контейнеры
docker image ls - посмотреть все образы
docker inspect <image> - изучить образ (размер и тд)
