# B9122-09.03.04-Kuzmichev_Mikhail
## Требования

- Установленный `Docker`
- Установленный `Docker Compose`

## Запуск

1. При необходимости создайте `.env` на основе `.env.example`.
2. Из корня проекта выполните:

```powershell
docker compose up --build -d
```

## Доступные сервисы

- Frontend: `http://localhost:4200`
- Backend API: `http://localhost:8000`
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`
- PostgreSQL: `localhost:5432`