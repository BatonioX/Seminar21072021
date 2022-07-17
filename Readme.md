# Инструкция по работе c Git

## Подготовка репозитория
Для создания репозитория используется команда "git init". В терминале в папке с будующим репозиторием достаточно написать "git init",и эта папка станет репозиторием.

## Добавление файла в коммит
Для добавления файла в текущий коммит используется комманда *git add*. ДЛя этого достаточно в терминале с папкой текущего репозитория написать *git add <название файла>*.

## Сохранения коммита
Для сохранения коммита используется комманда *git commit*. Для этого в терминале с папкой репозитория необходимо написать комманду *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***

### Просмотр состояния репозитория
Для просмотра состояния репозиторя используется комманда *git status*.Для этого в терминале с папкой репозитория необходимо написать комманду *git status*.

### Добавление файла в коммит
Для добавления файла в текущий коммит используется комманда *git add*. ДЛя этого достаточно в терминале с папкой текущего репозитория написать *git add <название файла>*.

## Фиксация изменений
Для сохранения коммита используется комманда *git commit*. Для этого в терминале с папкой репозитория необходимо написать комманду *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Журнал изменений
Для просмотра истории коммитов, то есть истории наших изменений используется комманда *git log*. Для этого необходимо в терминале с папкой-репозиторием написать *git log*.

## Перемещение между коммитами
Для того, чтобы перемещаться коммитами необходимо использовать комманду *git checkout*. Для этого в терминале с папкой репозитория необходимо написать *git checkout <номер коммита>*. Номер коммита берется из истории изменений. После такого "перемещения" мы попадаем в состаяние *Detached head*. Для возвращение в обычное состояние используется комманда *git checkout master* . 
## Ветки в Git
Для создания веток в git используется комманда *git branch*. Для этого необходимо в терминале с папкой-репозиторием написать *git branch <имя ветки>*.

## Перемещение между ветками
Для перемещения между ветками используется комманда *gir checkout branchname*.Для этого необходимо в терминале с папкой-репозиторием написать *git checkout <имя ветки>*. Для возврата в корневую ветвь используется команда *git checkout master*.

## Обьединение веток 
Для обьединения ветки с основным файлом используется  комманда *git merge*. Для этого в терминале с папкой репозитория необходимо написать *git merge <имя ветки>* .

## Удаление веток
Для удаления ветки неоходиммо ввести в терминале с папкой текщего репозитария команду *git branch -d<название ветки>*.

## Решение конфликтов
При слиянии веток могут повлятся конфликты,если в одной и той же строке в разных ветвятвях находятся разные данные.В таком случае Git выделит конфликтные строки и даст пользавателю информацию.Конфликт решается либо автоматически с помощью меню,либо вручную. После решения конфликта нужно сохранить файл и ***ОБЯЗАТЕЛЬНО*** сделать коммит.
