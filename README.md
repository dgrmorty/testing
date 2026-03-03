# Сайт — Маникюр в Минске

Статический сайт студии маникюра. Готов к деплою на [Railway](https://railway.app).

## Деплой на Railway

1. Зайдите на [railway.app](https://railway.app) и войдите через GitHub.
2. **New Project** → **Deploy from GitHub repo**.
3. Выберите репозиторий `dgrmorty/testing`.
4. Railway сам определит Node.js и команду `npm start`.
5. В настройках сервиса откройте **Settings** → **Networking** → **Generate Domain**, чтобы получить публичный URL.
6. После деплоя сайт будет доступен по выданному домену (например, `https://testing-production-xxxx.up.railway.app`).

## Локальный запуск

```bash
npm install
npm start
```

Сайт откроется на http://localhost:3000 (или на порту из переменной `PORT`).

## Структура

- `index.html` — главная страница
- `Маникюр в Минске _ Профессиональный nail-дизайн _ Студия красоты_files/` — стили, скрипты и изображения
