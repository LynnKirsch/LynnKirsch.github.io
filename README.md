# GitHub Pages redirect → tinymods.ru

Этот репозиторий предназначен **только для переадресации** со старого адреса `https://lynnkirsch.github.io/` на основной сайт [tinymods.ru](https://tinymods.ru/).

- **`redirect/index.html`** — перенаправление с сохранением путей, параметров запроса и якорей. Удаляет старый префикс `/tinymods`.
- **`.github/workflows/deploy-pages.yml`** — публикует в GitHub Pages только страницу перенаправления и её копию `404.html` для старых вложенных адресов.
- Для страниц указан `noindex`. GitHub Pages — статический хостинг, поэтому здесь клиентский редирект, а не серверный HTTP 301.

**Основной проект:** [LynnKirsch/tinymods](https://github.com/LynnKirsch/tinymods). Разработка ведётся только там.

**Точка восстановления старой копии:** ветка [`backup-tinymods-2026-11-02`](https://github.com/LynnKirsch/LynnKirsch.github.io/tree/backup-tinymods-2026-11-02). Её можно удалить отдельно, когда резервный снимок точно не потребуется.
