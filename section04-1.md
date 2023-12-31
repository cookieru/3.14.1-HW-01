[<< Вернуться к оглалению](README.md) | [^ Основы работы с репозиторием](section04.md)

[< Предыдущий раздел](section04.md) | [Следующий раздел >](section04-2.md)

Команда git status
----------------------------------------------

Один из основных инструментов, который помогает определить состояние файлов в Git, - это команда `git status`. Когда вы выполняете эту команду сразу после клонирования репозитория, вы получаете информацию о статусе файлов. Результат может выглядеть примерно так:

![Скрин git status в новом репозитории](https://github.com/cookieru/3.14.1-HW-01/blob/be6e80c7164a8bb750fa7c774b680c1fb3bebd72/images/2023-12-18%20174637.png?raw=true)

Это означает, что ваш рабочий каталог является чистым, то есть в нем нет отслеживаемых измененных файлов. Git также не обнаружил неотслеживаемых файлов, иначе они были бы перечислены. Команда также даёт вам информацию о текущей ветке.

Если вы добавили новый файл _README.md_ в свой проект, то при выполнении команды `git status` вы увидите его в разделе __Untracked files__.

![Скрин git status с новым файлом](https://github.com/cookieru/3.14.1-HW-01/blob/be6e80c7164a8bb750fa7c774b680c1fb3bebd72/images/2023-12-18%20174924.png?raw=true)

Это означает, что Git обнаружил файл, который не был отслеживаемым на предыдущем коммите. Файл не будет автоматически добавлен в следующий коммит, пока вы не укажете это явно. То есть, необходимо явно сообщить Git о том, что хотите включить этот файл в следующий коммит, используя команду `git add`. После этого Git начнет отслеживать изменения в файле и будет включать его в коммиты.

[<< Вернуться к оглалению](README.md) | [^ Основы работы с репозиторием](section04.md)

[< Предыдущий раздел](section04.md) | [Следующий раздел >](section04-2.md)