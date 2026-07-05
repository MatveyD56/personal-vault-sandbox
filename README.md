# personal-vault-sandbox

Волт-песочница «Личной ОС»: живое markdown-зеркало SQLite-БД (канон: personal-os/docs/architecture.md §3).
Правится руками в Obsidian; правки вливаются в БД через синк-цикл VPS.

- tasks/, crm/ — полный роунд-трип (файл-на-сущность)
- expenses/, calendar/, notes/ — export-only (ручная правка уезжает копией в conflicts/)
- backup/ — nightly-бэкапы БД
