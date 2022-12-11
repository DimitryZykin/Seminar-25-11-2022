# Инструкция по работе с Git.

## Чтотакое Git?
Git - это наиболее популярная система распределённая. 

## Подготовка репозитория. 

Для создания репозитория в папке репозитория необходимо написать команду git init. Для этого в терминале с открытой папкой 

## Добавление файлов к коммиту
Для добавления файлов к коммиту используется команда *git add*. Для того, чтобы добавить файл к новому коммиту необходимо в терминале с открытой папкой-репозитороием написать *git add <имя файла>*. 

### Создание коммитов
Для создания коммитов используется команда *git commit*. Для этого в папке с репозиторием необходимо написать команду *git commit -m "<сообщение к коммиту>"*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***

## Журнал изменений.
Для просмотра истории изменений используется команда *git log*. Для этого  в терминале с папкой-репозиторием необходимо набрать *git log*. 

## Перемещение между коммитами
Для перемещения между коммитами используется команда *git checkout*. Для этого в терминале с папкой-репозитеорием необходимо написать *git checkout <номер коммита>* Номера коммиттов можно посмотреть в истории коммитов, описанной в предыдущем пункте.

## Ветки в Гит.

Можно создавать несколько веток в Git, а потом их сливать в одну. Это позволяет работать над проектом нескольким людям одновременно. Или, например, разбить проект на несколько этапов и разграничивать их друг от друга для исключения перемешивания.

## Просмотр списка веток.
Для просмотра списка веток пишем команду git branch

## Слияние веток и решение конфликтов.
Чтобы провести слияние веток необходимо переключиться в ту ветку, куда будет производиться слияние и ввести в терминале команду *git merge <имя ветки>*.

## Удаление веток.
Для удаления ветки необходимо в терминале ввести команду *git branch -d <имя ветки>* предварительно сделав с ней слияние. В противном случае вы будете предупреждены о невыполненном слиянии.
