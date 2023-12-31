[<< Вернуться к оглалению](README.md) | [< Предыдущий раздел](section04.md) | [Следующий раздел >](section06.md)

Игнорирование изменений
=====================================

Если у вас есть группа файлов, которые вы не хотите автоматически добавлять в свой репозиторий и не хотите видеть в списке неотслеживаемых файлов, то вы можете создать файл .gitignore. Этот файл содержит шаблоны, которые указывают Git'у игнорировать определенные файлы или папки при отслеживании изменений.

[Пример файла .gitignore](.gitignore)

К шаблонам в файле .gitignore применяются следующие правила:

+ Пустые строки, а также строки, начинающиеся с #, игнорируются.
+ Стандартные шаблоны являются глобальными и применяются рекурсивно для всего дерева каталогов.
+ Чтобы избежать рекурсии используйте символ слеш (/) в начале шаблона.
+ Чтобы исключить каталог добавьте слеш (/) в конец шаблона.
+ Можно инвертировать шаблон, использовав восклицательный знак (!) в качестве первого символа.

Правила описываются с помощью [Glob-шаблонов](https://ru.manpages.org/glob/7)

[<< Вернуться к оглалению](README.md) | [< Предыдущий раздел](section04.md) | [Следующий раздел >](section06.md)