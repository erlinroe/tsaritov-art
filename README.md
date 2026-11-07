# TSARITOV.ART

Статический лендинг-портфолио Артура Царитова. Работает без сборщика и зависимостей: достаточно открыть `index.html` или раздать папку любым статическим сервером.

## Локальный запуск

```bash
python3 -m http.server 8000
```

После этого откройте `http://localhost:8000`.

## Обновление сайта

```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Pages автоматически опубликует изменения из ветки `main`.

## Свой домен

Когда домен DigitalPlat будет готов, укажите его в настройках GitHub Pages (`Settings → Pages → Custom domain`). GitHub создаст файл `CNAME`; его нужно сохранить в репозитории. На стороне DNS добавьте записи, которые покажет GitHub, затем включите `Enforce HTTPS`.
