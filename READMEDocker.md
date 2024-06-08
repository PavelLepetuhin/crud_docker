### Запуск сервера Django с использованием Docker

1. Создать отбраз 
```bash
docker build -t crud .
```
2.Запускаем контейнер
```bash
docker run -d -p 8000:8000 crud
```