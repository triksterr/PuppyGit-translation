# PuppyGit-translation

PuppyGit russian translation  
Русский перевод программы PuppyGit

PuppyGit - это программа для работы с локальными и удаленными [Git](https://git-scm.com/) репозиториями для [Android](https://ru.wikipedia.org/wiki/Android).

[Репозиторий программы и последние версии с русским переводом](https://github.com/catpuppyapp/PuppyGit)  

[Оригинальный английский файл](https://github.com/catpuppyapp/PuppyGit/blob/main/app/src/main/res/values/strings.xml)  

[Файл перевода в репозитории PuppyGit](https://github.com/catpuppyapp/PuppyGit/blame/main/app/src/main/res/values-ru/strings.xml)  

***Если вы нашли в русском переводе ошибку или неточность, пожалуйста, сообщите мне.***  
Вы также можете присоединиться к нам в качестве переводчика здесь.  
Для этого [создайте Issue (заявку) в данном репозитории](https://github.com/triksterr/PuppyGit-translation/issues).

Приятного и комфортного использования **PuppyGit** на русском языке!

## Инструкция по переводу для PuppyGit:
1. Скачайте файл [strings.xml](https://github.com/catpuppyapp/PuppyGit/blob/main/app/src/main/res/values/strings.xml).  
2. Переведите значения в файле на русский язык, например: `<help>help translate</help>` -> `<help>перевод справки</help>`  
3. Создайте Issue (заявку) в [оригинальном репозитории](https://github.com/catpuppyapp/PuppyGit), прикрепив к ней переведённый файл. В заявке укажите русский язык перевода.  
4. ***Примечание:***  
Строки в файле strings.xml вида `"ph_a3f241dc_NUMBER"` являются подстановочными переменными-заполнителями. Последнее число в строке обозначает позицию переменной.  
Например, строка ресурса: `<str1>name: ph_a3f241dc_1, age: ph_a3f241dc_2</str1>` заменяется при выполнении программы так, что вместо имен переменных подставляются значения, например: **`"name: abc, age: 123"`**.  
Если вы случайно перепутаете при переводе порядок номеров, например так: `<str1>name: ph_a3f241dc_2, age: ph_a3f241dc_1</str1>` - это может привести к неправильному отображению текста в приложении, например:
**`"name: 123, age: abc"`**.  
