# Курсовая работа: персональный сайт

Учебный сайт Валерия Половинкина на MkDocs с темой Material. Содержимое
представляет демонстрационное портфолио экономического аналитика.

## Запуск в Windows PowerShell

Из папки `coursework` выполните:

```powershell
py -m venv .venv
.venv\Scripts\python -m pip install -r requirements.txt
.venv\Scripts\python -m mkdocs serve
```

После запуска сайт доступен по адресу <http://127.0.0.1:8000/>.

## Сборка

```powershell
.venv\Scripts\python -m mkdocs build --strict
```

Готовые статические файлы создаются в папке `site`.
