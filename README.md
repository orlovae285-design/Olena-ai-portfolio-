# Olena AI — Portfolio

Сайт-візитка AI-креатора. Статика (один `index.html`), палітра 2026:
обсидіан + шампань-платина + титан, шрифт Fraunces.

---

## Крок 1 — Залити на GitHub

### Найпростіше (без термінала, через браузер)
1. Зайди на github.com → **New repository**.
2. Назви, наприклад, `olena-ai-portfolio`. Постав **Public** або **Private**. Створи.
3. На сторінці репозиторію: **Add file → Upload files**.
4. Перетягни ВСІ файли й папку `public` із цього проєкту.
5. Внизу натисни **Commit changes**.

### Через термінал (якщо зручно)
```bash
cd portfolio
git init
git add .
git commit -m "Перший коміт: портфоліо"
git branch -M main
git remote add origin https://github.com/ТВІЙ_ЛОГІН/olena-ai-portfolio.git
git push -u origin main
```

---

## Крок 2 — Підключити Vercel (авто-деплой)
1. vercel.com → **Add New → Project → Import Git Repository**.
2. Вибери щойно створений репозиторій → **Deploy**.
3. Готово. Тепер **кожна зміна в GitHub автоматично оновлює сайт.**

Свій домен `enjoy.net.ua`: Vercel → Project → Settings → Domains → Add.

---

## Крок 3 — Додати роботи (пізніше)
Зараз фото/відео тимчасово беруться зі старого сайту.
Коли покладеш роботи в `public/portfolio/`:
1. Завантаж файли туди (ті самі назви, що в `index.html`).
2. У `index.html` заміни:
   `const ASSET_BASE = "https://...chatgpt.site/";`  →  `const ASSET_BASE = "";`
3. Закоміть — сайт оновиться сам.

Сертифікат уже на місці: `public/portfolio/alpi-certificate.png`.

---

## Контакти на сайті
- Telegram → @orlovaolena8
- Instagram → @olena.ai_creator
