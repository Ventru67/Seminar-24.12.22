# Инструкция к Git

## 4то такое Git
Git - это наиболее популярная реализация системы контроля версии. Самая популярная реализация **Git** это [GitHub] (github.com)

## Подготовка репозитория
Для создания репозитория необходимо в терминале перейти в пустую папку, где в будущем будет репозиторий. Затем в терминале написать *git init*

## Добасление файлов к коммиту
Для добавления файлов к коммиту используется команда *git add* Для этого в трерминале с папкой репозитория необходимо написать *git add <название файла>*

## Создание коммита
Для создания коммита используется команда *git commit* для этого в папке репозитория необходимо написать *git commit -m "сообщение к коммиту"* Сообщение к коммиту писать **обязательно** 

## Перемещение коммитов

## Журнал изменений
Для просмотра журнала изменений используется команда git log. Для этого в терминале с папкой-репозиторием необходимо написать git log

## Перемещение между коммитами
Для перемещения между коммитами используется команда git chekout для этого необходимо в журнале изменений, как показано в предыдущей 4асти найти нужный коммит и его номер, после 4его в терминале с папкой репозиторием написать команду *git checkout <номер коммита>. После применения этой команды  вы попадете в состояние Detached head, в котором никакие изменения фиксироваться не будут. Для возврата в оы4ное состояние необходимо написать команду *git checkout master*

## Ветки в Git

## Слияние веток и разрешение конфликтов

## Удаление веток
