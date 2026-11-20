# WeatherHealth — интерактивная документация

Комплект технической документации мобильного приложения **WeatherHealth**. Документация подготовлена в Markdown и организована как связанный набор страниц с внутренней навигацией.

## Просмотр

- Откройте `docs/index.md` в Visual Studio Code и используйте Markdown Preview.
- Либо установите MkDocs и запустите локальный сайт:

```bash
python -m pip install -r requirements.txt
mkdocs serve
```

После запуска откройте адрес, который выведет MkDocs (обычно `http://127.0.0.1:8000`).

## Структура

```text
WeatherHealth_Interactive_Documentation/
├── README.md
├── mkdocs.yml
├── requirements.txt
└── docs/
    ├── index.md
    ├── quick-start.md
    ├── installation.md
    ├── user-guide.md
    ├── reference.md
    ├── architecture.md
    ├── troubleshooting.md
    └── images/
        ├── architecture.svg
        └── user-flow.svg
```

## Важное замечание

Документация описывает проект по материалам отчёта о практике. Точные URL собственных API, имена переменных окружения, версии зависимостей и параметры развёртывания в исходном описании не зафиксированы. Поэтому такие значения обозначены как настраиваемые или приведены как примеры, а не как подтверждённые параметры готового сервера.

[Открыть главную страницу документации](docs/index.md).
