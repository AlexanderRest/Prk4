# Угадай число (Клиент-Сервер)

Проект состоит из двух программ:
- Сервер (`server.c`) — загадывает число и отвечает на попытки клиента.
- Клиент (`client.c`) — пытается угадать число с помощью бинарного поиска.

## Компиляция и запуск

### Сервер
```bash
./src/Prk4_server 8080
```

### Клиент
Выполнить в другом терминале
```bash
./src/Prk4_client 127.0.0.1 8080
```
