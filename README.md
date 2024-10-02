# Домашнее задание к занятию «1.3. Architecture Components. Часть 2»

## Задача. Refresh to Prepend
### Описание
Измените код из лекции так, чтобы:

1. Автоматический PREPEND был отключен, т. е. при scroll к первому сверху элементу данные автоматически не подгружались.
2. REFRESH не затирал предыдущий кеш, а добавлял данные сверху, учитывая ID последнего поста сверху. Соответственно, swipe to refresh должен добавлять данные, а не затирать их.
3. APPEND работал в обычном режиме.
   
   
Убедитесь, что ваше приложение нормально функционирует при следующих сценариях работы:

1. Чистая установка — БД пустая.
2. Запуск с заполненной БД — в БД остались данные с предыдущего запуска.

### Результат
Опубликуйте изменения в виде Pull Request в вашем проекте на GitHub.
