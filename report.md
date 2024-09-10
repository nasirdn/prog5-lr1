# Закаблукова Анастасия Эдуардовна ИВТ-1.1
## Лабораторная работа №1. Реализация удаленного импорта.

Первый шаг.
Создать файл *myremotemodule.py*, который будет импортироваться и разместить его в каталоге *rootserver*.
![](images_report/pic1.png)

Второй шаг.
Разместить в этом файле код.
![](images_report/pic2.png)

Третий шаг.
Создать файл *activation_script.py*, который будет содержать функцию url_hook и классы URLLoader и URLFinder.
![](images_report/pic3.png)

Четвертый шаг.
Запускаем сервер.
![](images_report/pic4.png)

Пятый шаг.
Запускаем файл *activation_script.py*.
![](images_report/pic5.png)

Шестой шаг.
Добавляем путь, где располагается модуль в *sys.path*.
![](images_report/pic6.png)
![](images_report/pic7.png)

Седьмой шаг.
Импортируем файл *myremotemodule.py*, в котором размещена функция *myfoo*.
![](images_report/pic8.png)
