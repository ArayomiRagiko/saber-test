# Русская инструкция: Решение тестового задания от Saber Interactive

В этом репозитории находится готовое решение для тестового задания от Saber Interactive.

You'll find English version of this README below.

## Локальная сборка сайта

Для локальной сборки скачайте репозиторий.

Для дальнейшей работы вам необходимо установить [Python](https://www.python.org/downloads/) и **pip** актуальной версии.

Для генерации сайта я использую **mkdocs** и тему **material**.
Плагины для генерации сайта: **mkdocs-build-plantuml-plugin**, **mkdocs-glightbox**.

Для быстрой установки всех зависимостей введите команду:

    pip install -r requirments.txt

После этого введите команду:

    mkdocs serve

По умолчанию сайт будет собран по ссылке http://localhost:8000 или http://127.0.0.1:8000.

## Структура документации

| Элемент структуры | Описание |
|---|---|
| docs | Директория со всеми исходниками документации. |
| diagrams | Директория с диаграммами. В папке `src` находятся исходники всех диаграмм в проекте. |
| images | Директория с картинками для документации. |
| first-task.md | Файл-исходник для первого задания. |
| index.md | Файл-исходник для главной страницы. |
| second-task.md | Файл-исходник для второго задания. |
| .gitignore | Стандартный файл для работы с git. Нужен для игнорирования ненужных файлов. |
| mkdocs.yml | Файл для конфигурирования mkdocs. |
| requirments.txt | Файл с зависимостями проекта. |

# English instruction: Solution for the test task from Saber Interactive

This repository contains a ready-made solution for the test task from Saber Interactive.

Русская версия README находится выше.

## Local website build

For a local build, download the repository.

For further work, you need to install latest versions of the [Python](https://www.python.org/downloads/) and pip.

For site generation, I use **mkdocs** and the **material** theme.
Plugins for site generation: **mkdocs-build-plantuml-plugin**, **mkdocs-glightbox**.

For quick installation of all dependencies, enter the command:

    pip install -r requirements.txt

After that, enter the command:

    mkdocs serve

By default, the website will be built at the link http://localhost:8000 or http://127.0.0.1:8000.

## Documentation structure

| Structure Element | Description |
|---|---|
| docs | Directory with all documentation sources. |
| diagrams | Directory with diagrams. The `src` folder contains the source files for all diagrams in the project. |
| images | Directory with images for documentation. |
| first-task.md | Source file for the first task. |
| index.md | Source file for the main page. |
| second-task.md | Source file for the second task. |
| .gitignore | Standard file for working with git. Used to ignore unnecessary files. |
| mkdocs.yml | File for configuring mkdocs. |
| requirements.txt | File with project dependencies. |