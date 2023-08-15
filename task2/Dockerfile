FROM node:16-alpine

# Устанавливаем рабочую директорию внутри контейнера
WORKDIR /home/ilovedocker/app

# Копируем файл hello.sh в рабочую директорию контейнера
COPY hello.sh .

# Задаем команду запуска контейнера
CMD ["sh", "-c", "./hello.sh"]