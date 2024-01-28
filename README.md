# Проект парсинга pep

Парсер собирает данные обо всех PEP документах, сравнивает статусы и записывает их в файл, также реализованы сбор информации о статусе версий, скачивание архива с документацией и сбор ссылок о новостях в Python, логирует свою работу и ошибки в командную строку.

# Технологии проекта

- Python
- BeautifulSoup4
- Prettytable
- Logging

# Как запустить проект

Клонировать репозиторий и перейти в него в командной строке

```
git clone git@github.com:madina-zvezda/bs4_parser_pep.git
```

```
cd bs4_parser_pep
```

Создать и активировать виртуальное окружение

```
python3 -m venv venv
```

```
. venv/bin/activate
```

Установить зависимости из файла requirements.txt
```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

## Автор 
Муминова Мадина
