# Портфолио Ивана: сайты с онлайн-записью

- `index.html`: главная страница портфолио
- `demos/barbershop/index.html`: демо-сайт барбершопа BORODA с рабочей онлайн-записью

## Как опубликовать на GitHub Pages

1. Зарегистрируйтесь на github.com.
2. Создайте новый репозиторий с именем `ВАШ_НИК.github.io` (Public).
3. Нажмите **Add file → Upload files** и перетащите **содержимое** папки `site` (файл `index.html`, папку `demos`, этот README).
4. Нажмите **Commit changes**.
5. Откройте **Settings → Pages** и выберите Source: *Deploy from a branch*, Branch: `main`, папка `/ (root)`, затем **Save**.
6. Через 1–2 минуты сайт будет доступен по адресу `https://ВАШ_НИК.github.io`.

## Что заменить перед отправкой клиентам

В `index.html` найдите и замените:
- `https://t.me/your_username`: ваш Telegram
- `https://wa.me/79000000000`: ваш номер WhatsApp
- цены в блоке «Чем могу помочь», если нужно

## Как добавить новый проект

1. Создайте папку `demos/название/` с файлом `index.html`.
2. В `index.html` портфолио скопируйте блок `<article class="project">...</article>` и поменяйте ссылки и текст.
