# ᑌᑎᔕIᘔ ᗩᑎIᗰE — жеке веб-сайт

Бұл жоба MySubStudio-ға қатысы жоқ. Ол тек **ᑌᑎᔕIᘔ ᗩᑎIᗰE** арнасына арналған.

## Қамтылғаны
- Premium dark дизайн
- Desktop + mobile responsive
- Hero басты экран
- Аниме каталогы
- Жанр фильтрі
- Іздеу
- Аниме detail page
- Сериялар
- Video player
- Қазақша субтитр/дубляж/сапа метадеректері
- Telegram интеграция батырмасы
- Admin login
- Аниме қосу/өшіру
- Серия қосу/өшіру API
- Постер/видео upload API
- Сайт баптаулары
- JSON database

## Орнату
Node.js 18+ керек.

```bash
npm install
```
`.env.example` файлын `.env` қылып көшіріп, `ADMIN_PASSWORD` мәнін ауыстыр.
Содан кейін:

```bash
npm start
```

`http://localhost:3000` аш.
Admin: `http://localhost:3000/#admin`

## Production
Үлкен видео архив үшін `uploads/videos` орнына Cloudflare R2/S3 + CDN және HLS қолданған дұрыс. Frontend бұл URL-мен жұмыс істейді.

Тек таратуға құқықтарыңыз бар контентті орналастырыңыз.
