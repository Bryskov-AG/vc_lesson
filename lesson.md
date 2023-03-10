# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Команда CLONE

Для начала работы с удалённым центральным репозиторием,нужно создать копию.Клонируем проект на свой компьютер,используя команду *git clone* с добавлением ссылки на удалённый репозиторий.
## Команда PUSH

После проведения работы в экспериментальной ветке, слияния с основной, необходимо обновить удаленный репозиторий (удаленную ветку). Для этого используется команда *git push*.

## Команда PULL

Для синхронизации текущей ветки с репозиторием использутся команд *git pull*.Команда забирает изменения и проводит слияние с активной веткой.

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## P.S.

> В древности люди учились для того, чтобы совершенствовать себя. Ныне учатся для того, чтобы удивить других. 

> [Конфуций](https://ru.wikipedia.org/wiki/Конфуций).

![Конфуций](Confucius.j).

Сегодня прекрасная погода!

Books,books,books.

Ещё больше книг.

И снова книги!


Чёрный — тон, отсутствие светового потока от объекта. В системе HTML-цветов обозначается как #000000. Оттенки чёрного цвета именуются серым цветом. Чёрный цвет является ахроматическим цветом, то есть цветом без оттенка, подобно белому и серому[1]. Он часто используется символически или фигурально для обозначения тьмы, а белый — для света[2]. Чёрное и белое часто использовались для описания противоположностей, таких как добро и зло, тёмные века против эпохи Просвещения и ночь против дня. Со времён средневековья чёрный цвет являлся символом торжественности и авторитета, и по этой причине его всё ещё часто носят судьи, магистраты и др.

Серый цвет — это ахроматический цвет, точнее — множество всех цветов, получаемых путём совмещения трёх основных цветов цветовой модели RGB — красного, зелёного и синего в равных концентрациях. В зависимости от яркости оттенок серого изменяется от чёрного (яркость 0 %) до белого (яркость 100 %). В цветовой модели CMYK серый цвет может быть образован из первых трёх цветов (CMY), при этом пропорции триадных красок чаще не одинаковы, или изменением четвёртого цвета (K) от 0 (белый) до 100 (чёрный), или комбинацией этих вариантов. Старинный синоним серого — срений.

Кра́сный (родственно ст.‑слав. красьнъ ‘красивый, прекрасный’), также червлёный, червонный, пунцовый, алый, багряный, багровый, рдяный (арх.) — область цветов в длинноволновой части видимого спектра, соответствует минимальным частотам электромагнитного излучения, воспринимаемого человеческим глазом. Диапазон красных цветов в спектре часто определяют длинами волн 630—760 нанометров[1][2][3][4][5], что соответствует частотам 476—394 терагерц. Длинноволновая граница восприятия зависит от возраста человека

Бе́лый цвет — цвет со спектром электромагнитного излучения равномерной мощности по всем длинам волн в видимой части. Является так называемым ахроматическим цветом, вместе с чёрным и оттенками серого. 
