FROM node:16-alpine
WORKDIR /home/ilovedocker/app

# Копируем файлы package.json и package-lock.json в корень рабочей директории контейнера
COPY packages/package.json packages/package-lock.json ./

# Копируем исходники проекта из поддиректории src в корень рабочей директории контейнера
COPY src ./

# Устанавливаем зависимости при помощи npm
RUN npm install

# Экспонируем порт 3032
EXPOSE 3032

# Задаем команду запуска контейнера
CMD ["node", "main.js"]

