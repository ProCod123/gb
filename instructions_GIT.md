![Эмблемма GIT](git.png)

# Инструкция по работе с ГИТ. 

*Для того чтобы GIT мог включить поддержку контроля версии в каком-либо каталоге, необходимо перейти в данный каталог и выполнить команду:*  
**git init**

*После инициализации необходимо создать учетную запись в системе, это позволит создавать коммиты. Необходимо ввести имя пользователя и адрес электронной почты. Сделать это можно с помощью команд:* 

git config --global user.name "Aleksandr"
git config --global user.email ucheba11univer@gmail.com

*Проверить все ли работает корректно можно с помощью команды:*

**get status**

*Для внесения в список файлов к которым должна применяться система контроля версии необходимо выполнить команду:*

git add имя файла.расширение

*Например:* git add mark.md

*Теперь, после того как в файл будут вноситься изменения для которых нужен коммит, нужно будет выполнить последовательность команд:*

1. **Сохранить файл (ctl + s)**
2. **git add mark.md**
3. **commit -m "Текст коммита"**

*Для просмотра имеющихся коммитов можно воспользоваться командой:*

**git log**

*Для перехода к какому-либо коммиту необходимо используя 4 и более цифры (полученные в результате команды git log) указать в команде:*

**git checkout  79eaf**

*Для перехода к актуальной версии файла можно воспользоваться космандой:*

**git checkout master**

*Для просмотра отличий можду текущим и закомиченным файлом:*

**git diff**






