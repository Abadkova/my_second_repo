# Инструкция для работы с Git и удаленными репозиториями
 
 ## Что такое Git?
 Git - это одна из реализаций распределенных системконтроля версий, имеющая как и локальные,так и удаленные  репозитории. Является самой популярной реализацией систем контроля версий в мире.
 ## Подготовка репозитория
 Для создания необходимо выполнить команду *git init* в папке с репозиторием и у нас создастся репозиторий (появится срытая папка .git
 
 ## Создание коммитов
 ### Git add
 *git add <имя файла>* - добавление изменений в коммит
 
 ### Просмотр состояния репозитория
 *git status* - посмотреть состояние репозитория(были изменения или не было)
 
 ### Создание коммитов
 *git commit -m "Коментарий к записи"* - фиксирует изменения и сообщает о появлении новых версий файлов.
 
 *git log* -выводит список всех сохранений в хронологическом порядке.

 *git dif* - показывает разницу между уже зафиксированной версией файла и текущей.


 *git checkout* - позволяет перемещаться между сохранениями.)

 # удаление файла в windows
 ~~~ sh
 del <filename>
 ~~~
  
## Добавим картинку ##

Это медведь

![Панда](scale_1200.jpg)

* git branch* - вывести список всех имеющихся команд

*git branch <имя  новой ветки> - создать новую ветку

* git checkout <имя ветки> - перейти на новую ветку

* git merge 
 <имя ветки, которую будем сливать с основной> - слить ветки

* git branch _d <имя ветки> - удалит уже слитую ветку

* git log --graph - увидеть лог коммитов с визуализацией между ними

* git diff - показывает, что было изменено

* git log - выводим список всех коммитов(сохранений)

* git log --oneline - показать все коммиты в виде одной строки

* Q - выход из этого состояния.
* 
* ## Добавим новые командЫ ##

*Git clone* - позволяет склонировать внешний репозиторий на наш ПК.

*git pull* - позволяет скачать всё из текущего репозитория и автоматически сделать *merge* c нашей версией.
 
 *Git push* - позволяет отправить нашу версию репозитория на внешний репозиторий (требуется авторизация на внешним репозитории).

 *git clean* - используется для удаления мусора из рабочего каталога.


