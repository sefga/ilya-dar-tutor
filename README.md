# Ильдар Бекмухамбетов — сайт-портфолио репетитора

Статический one-page сайт: математика, физика, информатика (ОГЭ/ЕГЭ, онлайн).

**Live (VPS):** http://38.114.103.160:8765/  
**Telegram:** [@A1GEBR0](https://t.me/A1GEBR0)

## Структура

```
.
├── index.html          # лендинг
├── assets/
│   ├── ildar-portrait.jpg
│   └── ildar-profi.jpg
├── vercel.json         # деплой на Vercel (static)
└── README.md
```

## Скачать / клонировать

```bash
git clone https://github.com/sefga/ilya-dar-tutor.git
cd ilya-dar-tutor
```

ZIP с GitHub: **Code → Download ZIP**.

Локальный просмотр:

```bash
python3 -m http.server 8765
# http://127.0.0.1:8765/
```

## Vercel

Уже есть `vercel.json` (static, clean URLs).

### Через CLI (после `vercel login`)

```bash
cd ilya-dar-tutor
vercel          # preview
vercel --prod   # production
```

### Через Dashboard

1. [vercel.com/new](https://vercel.com/new)
2. Import GitHub repo `sefga/ilya-dar-tutor`
3. Framework: **Other** / static
4. Root: `.` · Build: none · Output: `.`
5. Deploy

Нужны: аккаунт Vercel + доступ к репо (или `VERCEL_TOKEN` для CLI).

## Лицензия / контент

Материалы профиля — для личного сайта Ильдара Бекмухамбетова.  
Фото и тексты из публичных анкет (Profi / Яндекс / Repetit) + согласование с автором.
