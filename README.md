# Парсер книг 2.0 с сайта tululu.org

Программа скачивает книги в папку books/, картинки к ним в папку images/ и выводит описание книги в консоль.

### Как установить

Python3 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```python
pip install -r requirements.txt
```

### Аргументы

Для запуска программы используйте команду ниже в папке проекта. Укажите страницу каталога с научной фантастикой, с которой нужно начать скачивать, после аргумента `--start_page` и страницу каталога с научной фантастикой, до которой нужно скачивать, после аргумента `--end_page`. Укажите аргумент `--skip_txt`, если не хотите скачивать книги, и аргумент `--skip_imgs`, если не хотите скачивать обложки к книгам. Укажите путь для скачивания книг и обложек после аргумента `--dest_folder` и путь к JSON файлу с информацией о книгах после аргумента `--json_path`. Пример:
```python
python main.py --start_page <страница> --end_page <страница> --skip_txt --skip_imgs --dest_folder <путь> --json_path <путь_к_json>
```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).