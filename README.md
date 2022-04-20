
##  Мини терминал jusan-cli с небольшим количеством команд 
#### Для запуска программы зайдите в коммандную строку перейдите в папку с файлом jusan-cli.jar а затем исполните следующую команду
```
java -jar jusan-cli.jar
```
#### Сами команды:
```

ls <path>               выводит список всех файлов и директорий для `path` - 
                        | например ls F:\Downloads\AngularReactiveFormsDemo-master

ls_py <path>            выводит список файлов с расширением `.py` в `path` - 
                        | например ls_py F:\Downloads\AngularReactiveFormsDemo-master

is_dir <path>           выводит `true`, если `path` это директория, в других случаях `false` - 
                        |  например is_dir F:\Downloads\AngularReactiveFormsDemo-master

define <path>           выводит `директория` или `файл` в зависимости от типа `path` - 
                        | например define потом если файл F:\Downloads\jusan-cli-main.zip

readmod <path>          выводит права для файла в формате `rwx` для текущего пользователя - 
                        | например readmod и путь к файлу F:\Downloads\jusan-cli-main.zip

setmod <path> <perm>    устанавливает права для файла `path` `perm`(read,write,execute) - 
                        | например setmod path(F:\Downloads\AngularReactiveFormsDemo-master) perm(read,write,execute)

cat <path>              выводит контент файла - 
                        | например cat и полный путь до файла  F:\Downloads\jusan-cli-main.zip 

append <path>           добавляет строку `# Autogenerated line` в конец `path` - 
                        | например append F:\Downloads\AngularReactiveFormsDemo-master

bc <path>               создает копию `path` в директорию `/tmp/${date}.backup` где, date - это дата в формате `dd-mm-yyyy`- 
                        | например bc F:\AngularReactiveFormsDemo

greplong <path>         выводит самое длинное слово в файле - 
                        | например greplong F:\AngularReactiveFormsDemo

help                    выводит список команд и их описание - 
                        | просто help 

exit                    завершает работу программы - 
                        | и здесь тоже просто exit
```

