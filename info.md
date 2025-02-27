Привет, GitHub и мир
Hello, GitHub
А ниже инструкция дополненная)

# Инструкция по работе с Git

## Команды

* git init - инициализация локального репозитария
* git status - получить информацию о текущем состоянии репозитария
* git add . - добавляет файл или файлы к следующему коммиту
* git commit -m "комментарий" - фиксирует изменения и сообщает о появлениии новых версий файлов c комментарием
* git log - выводит список всех коммитов (сохранений) в хронологическом порядке с хеш-кодами
* git checkout 1234 - переход к ветке 1234(1234-первые четыре символа хеш-кода)
* git checkout master - переход в актуальную запись ветки
* git diff - показывает разницу между текущей и уже сохраненной версией файла
* git branch – посмотреть список веток в репозитории
+ git branch <название ветки> – создать новую ветку
* git checkout <название ветки> – переход к другой ветке
* git branch -d <название ветки> – удалить ветку
* git merge <название ветки> - слияние веток
* git log --graph - просмотреть весь список коммитов

## Выделение текста 

Чтобы выделить текст курсивом, необходимо обрамить его звёздочками (*). Например, **вот так*.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звёздочками (**)  или двойным знаком нижнего подчёркивания (__). Например, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например,  _текст может быть выделенным курсивом и при этом быть **полужирным**_. 

Чтобы текст был зачеркнутый, необходимо обрамить его значком ~ (~). Например, ~вот так~.

## Списки

Чтобы добавить не нумерованные списки, необходимо пункты выделить звёздочкой (*) или знаком (+). Например, вот так:

* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать. Например, вот так:

1. Первый пункт
2. Второй пункт
## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее: 

![описание картинки](ссылка на картинку)

![Teftelka](Teftelka.jpg)
## Цитаты

Для отображения цитаты в начале текста необходимо оспользовать значок >. Например, 
> вот так.

## Ссылки

Для отоброжения ссылки, необходимо адрес ссылки обрамить значками <> (<>). Например, вот так:
<https://img.wallpapic.com/.>

## Работа с удалёнными репозиториями

* git remmote add original <ссылка> - указыает путь на удалённый репозиторий.
* git branch -m  main - указывает основную ветку.
* git push -u origan main - направляет наш репозиторий в локальный.
* git pull - позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией.
* git push - позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории
* git clone 

### Как сделать pull request

* Делаем fork репозитория
* Делаем clone СВОЕЙ версии репозитория
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request 