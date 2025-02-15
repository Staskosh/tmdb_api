# Скрипт для управления контентом на сайте [themoviedb](https://www.themoviedb.org/)
Данный проект предназначен для нахождения фильмов и определения рекомендаций из БД [themoviedb](https://www.themoviedb.org/).

##  Запуск
- Скачайте код
- Установите виртуальное окружение
- Установите требуемые пакеты при помощи команды:
```bash
pip install -r requirements.txt
```
- Необходимо зарегистрироваться на сайте [themoviedb](https://www.themoviedb.org/signup)
- Получить API key. Вы можете подать заявку на получение ключа API, щелкнув ссылку «API» на левой боковой панели на странице настроек вашей учетной записи. Чтобы подать заявку на ключ API, вам необходимо иметь легитимное название компании, адрес, номер телефона и описание.
### Для создания файла собственной БД необходимо запустить скрипт командой:
```bash
$python make_own_db.py
```
Если у вас уже есть файл MyFilmDB.json, то вы можете пропустить этот шаг.
- Введите API key. 
- Подождите 15-20 минут. (По умолчанию скачивается база данных с тысячей фильмов)
- У вас появится файл MyFilmDB.json в корне папки с проектом.  
### Для поиска фильма запустите скрипт командой:
```bash
$python search_in_db.py
```
1) Введите путь до файла MyFilmDB.json
2) Введите название фильма
3) Вы получите фильм или список фильмов согласно введенному названию
4) Наливаем чай и несем печеньки :)

### Если вы хотите найти похожие фильмы на ваш любимый, вы можете воспользоваться командой:
```bash
$python find_similar.py
```
1) Введите путь до файла MyFilmDB.json
2) Введите название фильма
3) Вы получите 8 рекомендованных к просмотру фильмов.
4) Наливаем чай и несем печеньки :)

## Цели проекта

Файл README.md написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).
