# Шпаргалка по Git

## Основные понятия
Терминал (командная строка) - в UNIX-системах программный интерфейс, который позволяет взаимодействовать с операционной системой путем ввода текстовых команд

Директория - объект в файловой системе, упрощающий организацию файлов и образующий иерархию файловой системы

Родительская директория - директория, находящаяся в иерархии на уровень выше текущей

Рабочая директория - текущая директория, в которой находится пользователь

Git - Система контроля версий (VCS), отслеживающая изменения в разных версиях файлов

Репозиторий - Централизованное цифровое хранилище, используемое командой
разработчиков для совместной работы над проектом

Коммит - Завершенное изменение в проекте, сохраняющееся в текущей ветке

Пуш - Команда, передающая изменения из локального репозитория в удалённый

## Основные команды для работы в терминале
### whoami - вывод имени пользователя
### pwd - вывод абсолютного пути к текущей директории
### ls - вывод файлов и директорий в рабочей директории
-l - вывод подробной информации по каждому файлу в том числе с правами доступа

-a - вывод в том числе и скрытых файлов и директорий (с точкой в начале имени)
### cd <название директории> - переход в директорию
~ - переход в домашнюю директорию (если не указать никакую директорию впринципе, переход так же будет в домашнюю директорию)

. - переход в текущую директорию

.. - переход в родительскую директорию
### mkdir <название директории> - создать директорию
### touch <название файла> - создать файл
### rmdir <название директории> - удалить пустую директорию
если директория не пустая, терминал не выполнит команду и выведет ошибку
### rm <название файла> - удалить файл
-r - удалить директорию со всеми находящимися там файлами
-f - убрать предупреждения при удалении файлов
### cat <название файла> - вывести содержимое текстового файла
### cp <копируемый файл> <путь, куда копируется файл> - скопировать файл
### mv <название файла> <путь, куда перемещается файл> - переместить файл

## Основные команды для работы с Git
### git init - создать репозиторий в рабочей директории
### git add <название файла> - добавить изменённый или созданный файл в коммит
### git commit - сделать коммит
-m "message" - добавить сообщение к коммиту, иначе произойдёт переход в текстовый редактор
### git log - просмотреть историю коммитов
### git push - отправить все изменения в удалённый репозиторий
