# Лабораторная работа №1

## Используемый датасет
*   **Название:** Real Estate Valuation (предсказание цены дома)
*   **Задача:** Регрессия
*   **Источник:** [UCI ML Repository, ID 477](https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set)
*   **Лицензия:** CC BY 4.0
*   **Примечание:** Файлы данных в репозиторий не коммитятся. Скачать датасет можно по ссылке выше.

## Содержимое репозитория
*   `lab1_0_Topakova.ipynb` — основной Jupyter Notebook с полным кодом, анализом и выводами.
*   `requirements.txt` — список зависимостей Python с зафиксированными версиями.
*   `.gitignore` — файл для исключения из репозитория данных и других временных файлов.
*   `README.md` — этот файл с описанием проекта.

## Инструкция по запуску

### 1. Клонирование репозитория
    git clone https://github.com/polina-topakova/Lab1_Deep_Learning.git
    cd Lab1_Deep_Learning

### 2. Скачивание данных
*   Скачайте файл `Real estate valuation data set.xlsx` по [ссылке](https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set).
*   Переименуйте его в `variant_0.xlsx`.
*   Создайте в корне проекта папку `data` и поместите файл туда. Итоговый путь: `data/variant_0.xlsx`.

### 3. Создание и активация виртуального окружения
    python3.12 -m venv .venv
    source .venv/bin/activate
    .venv\Scripts\activate

### 4. Установка зависимостей
    pip install -r requirements.txt

### 5. Запуск ноутбука
    jupyter lab

Откройте файл `lab1_0_Topakova.ipynb` и выполните все ячейки последовательно.

## Версия Python
Проект протестирован на Python 3.12.

## Воспроизводимость
*   Все случайные процессы засеяны (`RANDOM_STATE = 0`).
*   Версии пакетов зафиксированы в `requirements.txt`.
*   Запуск на чистом окружении не требует ручных правок.

## Автор
*   **ФИО:** Топакова Полина Васильевна
*   **Номер зачетной книжки:** 230470
*   **Вариант:** 0