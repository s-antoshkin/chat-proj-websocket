# Simple websocket chat

Простой чат-одностраничник, без регистрации и без храннения сообщений.

Показывает кто в сети, статус "сервера".

## Запуск проекта

- клонировать проект:
```ch
git clone https://github.com/s-antoshkin/chat-proj-websocket.git
```
- перейти в корневой каталог;
```ch
cd chat-proj-websocket
```
- установить зависимости:
```ch
go get -u
```
- выполнить команду:
```ch
go run cmd/web/*.go
```
- перейти в браузере (лучше в нескольких) на `localhost:8080`.

## Используемые библиотеки
- `gorilla/websocket`;
- `CloudyKit/jet`;
- `bmizerany/pat`.