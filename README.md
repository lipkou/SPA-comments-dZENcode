# SPA-приложение: Комментарии. 
**Тут я раскажу как запустить проект и что для этоно надо сделать.**
*Подрузомивается что вы уже установили проект у вас есть установлен [Doker](https://www.docker.com/products/docker-desktop/) и [PostgreSQL](https://www.postgresql.org/download/).*

### 1. Настроить `example.env`
1.1 Скопировать и переименовать `example.env` в `.env` (не удаляйте старый `example.env` если не хотите проблем с гитом)
1.2 Сгенерировать токен и заполнить данные в недостающихся переименных. 


### 2. Забилживаем образ:
2.1 Прописываем команду: `docker build -t dzencode_docker .` 

### 3. Подмимаем сайт:
3.1 Прописываем команду: `docker-compose up`

### 4. Переход на проект
5.1 Переходим на проект: http://localhost:8000/ (если вы у себя на машине настраивали)
