# Bittensor Lab

Это мой «лабораторный» репозиторий для анализа подсетей Bittensor.

Структура:
- `data/` — сюда кладу ZIP и `.log` (сырьё для анализа).
- `analysis/` — сюда автоматически попадает результат обработки (ветка `analysis` создаётся после запуска workflow).
- `notes/` — мои конспекты и выжимки.
- `manifest/repos.yaml` — список репозиториев, которые разбираю.

Как пользоваться:
1) Загружаю ZIP/логи в `data/`.
2) Вкладка Actions → запускаю workflow «Prepare data (unzip + split logs)».
3) Результаты смотрю в ветке `analysis` (папки `analysis/extracted` и `analysis/logs`).
4) Пишу короткие выжимки в `notes/` по шаблону `notes/template.md`.
