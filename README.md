# MirliLMS/.github

Общие настройки для всех репозиториев организации.

- `.github/ISSUE_TEMPLATE/` — шаблоны issue (баг, задача). Действуют во всех репозиториях без своих шаблонов.
- `.github/pull_request_template.md` — шаблон PR.
- `gitignore/` — `.gitignore` по стекам:

| Файл | Что внутри |
|---|---|
| `Mirli.gitignore` | Всё вместе — используй по умолчанию |
| `AI.gitignore` | Папки и файлы ИИ-инструментов |
| `Secrets.gitignore` | `.env`, ключи, сертификаты, креды, дампы БД |
| `CSharp.gitignore` | C# / .NET |
| `Rust.gitignore` | Rust |
| `Node.gitignore` | TypeScript, React, Tailwind, Ant Design |
| `Python.gitignore` | Python |
| `Docker.gitignore` | Docker, данные MySQL / MongoDB / S3 (MinIO) |
| `Common.gitignore` | ОС, редакторы, логи |

Добавить в существующий проект:

```sh
curl -fsSL https://raw.githubusercontent.com/MirliLMS/.github/main/gitignore/Mirli.gitignore >> .gitignore
```

Новый проект проще создавать из шаблона [`MirliLMS/project-template`](https://github.com/MirliLMS/project-template): там уже лежит `.gitignore`.
