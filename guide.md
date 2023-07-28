Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.
## Основные команды Git
* <span style="color:blue">*git init*</span> – инициализация локального репозитория.

* <span style="color:blue">*git status*</span> – получить информацию от git о его текущем состоянии.

* <span style="color:blue">*git add*</span> – добавить файл или файлы к следующему коммиту.

* <span style="color:blue">*git commit -m “message”*</span> – создание коммита.

* <span style="color:blue">*git log*</span> – вывод на экран истории всех коммитов с их хеш-кодами.

* <span style="color:blue">*git checkout*</span> – переход от одного коммита к другому.

* <span style="color:blue">*git checkout master*</span> – вернуться к актуальному состоянию и продолжить работу.

* <span style="color:blue">*git diff*</span> – увидеть разницу между текущим файлом и закоммиченным файлом.

### Частые вопросы по git:

#### Как отменить последний коммит?

Для этого используем команду git reset, ее можно применить в двух вариациях.

Первый вариант отменяет все изменения:

>git reset --hard HEAD~1

Второй вариант, если нужно сохранить всё, что вы сделали, но еще не успели закоммититье:

>git reset --soft HEAD~1

HEAD~1 означает один коммит до HEAD, т.е. до текущего положения.

#### Как отменить «git add» до коммита?

Если вы выполнили git add для какого либо файла по ошбике и хотите это отменить, то выполните команду:

>git reset имя_файла

Это поможет вслучае того, если коммит еще не был сделан

#### Как переименовать локальную ветку?

Это можно сделать командой:

>git branch -m oldname newname

#### Как восстановить удалённый файл?

<тута будет ответ <span style="color:gray">скоро*</span>>

<hr>
<span style="color:gray">Актуальный гайд по markdown</span> - [Кликай сюда](https://www.markdownguide.org/basic-syntax/ "https://www.markdownguide.org/basic-syntax/")

[<p align="right"><img src="geekbrains-logo.png" width="150"/></p>](/geekbrains-logo.png) 
