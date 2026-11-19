# Manicura Rusa · Daria (Villa Carlos Paz)

Мобильный сайт-визитка (Link-in-Bio / Taplink) для мастера маникюра Дарьи (`@manicura_ru`).  
Sitio web móvil (Link-in-Bio) para Daria — Manicura rusa en Villa Carlos Paz, Córdoba.

---

## Live Preview / Демо

https://liagr03-spec.github.io/manicura-rusa/

---

## Как установить сайт на свой домен / Cómo publicar en tu dominio

Сайт полностью статический (**HTML5 + CSS3 + Vanilla JS**). Не требует баз данных, PHP, Node.js или сборки.

### Вариант 1: Обычный хостинг (cPanel, Hostinger, DonWeb, Timeweb, Beget и др.)
1. Нажмите зелёную кнопку **Code → Download ZIP** (или перейдите по прямой ссылке: [Скачать ZIP](https://github.com/liagr03-spec/manicura-rusa/archive/refs/heads/main.zip)).
2. Распакуйте архив — внутри находятся файл `index.html` и папка `assets/`.
3. Загрузите `index.html` и папку `assets/` в корневую папку вашего домена (`public_html`, `www` или `htdocs`).
4. Убедитесь, что для домена включён бесплатный SSL-сертификат (`https://`).

### Вариант 2: Vercel / Netlify / Cloudflare Pages
1. Нажмите **Add New Project / Import from Git** и укажите ссылку на этот репозиторий:
   `https://github.com/liagr03-spec/manicura-rusa`
2. Настройки сборки:
   - **Framework Preset:** `Other` / `None`
   - **Build Command:** *(оставить пустым)*
   - **Output Directory / Publish Directory:** `.` (корень репозитория)
3. Подключите ваш домен в разделе **Domains**.

---

## Структура файлов / Estructura

```text
├── index.html          # Главная страница (стили, скрипты, SEO Schema.org, Open Graph)
└── assets/
    ├── stock/          # 12 фото сайта (обложка, портрет, студия, стерилизация, отзывы)
    └── works/          # 15 фото работ из карусели портфолио
```

---

## Контакты и ссылки внутри сайта
- **WhatsApp:** `+54 9 11 3300-9473` (кнопки записи открывают чат с готовым текстом на испанском)
- **Instagram:** https://instagram.com/manicura_ru
- **Локация:** Barrio Miguel Muñoz (cerca de Av. General Cárcano), Villa Carlos Paz, Córdoba — показана примерная зона без номера дома.
