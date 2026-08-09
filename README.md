# Miro-8 — официальный сайт

Deploy-ready статический сайт без сборщика и внешних библиотек.

## Публичные ссылки

- GitHub: https://github.com/mebelm161ru-bot
- Планируемый репозиторий: `miro8-site`
- Первый адрес GitHub Pages: https://mebelm161ru-bot.github.io/miro8-site/
- Будущий основной домен: https://miro8.ru/
- BandLink: https://band.link/ni0i1
- VK: https://vk.ru/miro8_music
- VK Артист: https://vk.ru/artist/4122223775008170793
- Spotify: https://open.spotify.com/artist/27loXOE9CcHSJKKcN0C9Wl

## Локальный запуск

```bash
python -m http.server 8000
```

Откройте `http://localhost:8000`.

Не используйте двойной клик `file://`: браузер может ограничить видео, буфер обмена и интерактивные действия.

## GitHub Pages

Загрузите всё содержимое этой папки в корень публичного репозитория `miro8-site`.

**Settings → Pages → Deploy from a branch → main / root.**

## Vercel

Создайте аккаунт через **Continue with GitHub**, импортируйте `miro8-site` и выберите Framework Preset **Other**. Команды сборки не требуются.

## Домен

Активный файл `CNAME` пока не добавлен, потому что DNS `miro8.ru` не настроен. После покупки домена используйте содержимое `CNAME_AFTER_DOMAIN_PURCHASE.txt` либо подключите домен через Vercel → Settings → Domains.

## Метрика

После публикации создайте счётчик Яндекс Метрики и добавьте его номер в `yandex-metrika-snippet.template.html` вместо `XXXXXXXX`.

Подробности: `00_ВАШИ_ДАННЫЕ_И_СЛЕДУЮЩИЕ_ШАГИ.docx` и `ЗАПУСК_САЙТА_GITHUB_И_VERCEL.docx`.
