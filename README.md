# Портфолио

Одностраничный сайт: кто я, какие проекты сделал, чем могу помочь.

**Открыть:** https://goodkiler1.github.io

## Устройство

Страница `index.html`, стили `styles.css`, шрифты в `fonts/`. Сайт ничего не грузит
с чужих серверов — так он открывается там, где заблокированы CDN.

| Что | Чем сделано |
|---|---|
| Разметка | HTML |
| Стили | Tailwind CSS, собран в `styles.css` |
| Шрифт | Geist и Geist Mono, лежат в `fonts/` |
| Хостинг | GitHub Pages |

## Как менять

Текст — прямо в `index.html`. Если добавил новые классы Tailwind, пересобери стили:

```
npx tailwindcss@3 -i src/input.css -o styles.css --minify
```

Потом отправить изменения:

```
git add -A
git commit -m "что изменил"
git push
```
