# Шаблон для маленького web-проекта на TypeScript 

Для разворачивания проекта необходимо установить [node.js](https://nodejs.org/en/download/)

После скачать шаблон проекта 
```
git clone https://github.com/vasiliy-uskov/typescript_template <project_name>
```
Переинициализировать git
Для windows:
```
cd ./<project_name>
rd /s .git
git init
git add --all
```
Для Linux
```
cd ./<project_name>
rm -rf .git
git init
git add --all
```
После выполнить в корне проекта команду ```npm install```, чтобы скачаь все необходимые для запуска пакеты node.js. 

Для сборки приложения в корне проекта выполнить
```
npm run build
```
Для запуска приложения в корне проекта выполнить
```
npm run start
```
