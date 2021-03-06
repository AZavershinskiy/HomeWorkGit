# **Инструкция по написанию текстов в MarkDown**
___
# *Оформление шрифта*

Жирный текст: ** (с двух сторон), пример: **это жирный текст**

Курсивный текст: * или _ (с двух сторон), пример: *это курсивный текст* и _это тоже курсивный текст_

Зачерунктый текст: ~~ (с двух сторон), пример: ~~это зачеркнутый текст~~

Пример комбинированного текста: *это* **комбинированный _~~текст~~_**
___
# *Оформление заголовка*

Выделение заголовка: # (только в начале строки, 6 значений), дальше через пробел сам заголовок, пример на следующей строке:
# Пример заголовока
## Пример заголовока
### Пример заголовока
#### Пример заголовока
##### Пример заголовока
###### Пример заголовока

Уровень заголовка: = или - (любое количество на следющей строке под нужным заголовком), примеры на следующих строках:

Пример заголовока первого уровня
===============
Пример заголовока второго уровня
---------------
___
# *Оформление списка*

Нумерованный список: арабские цифры 1., 2., 3. и т. д., например:
1. Первый
2. Второй
3. Третий

Ненумированный список через маркеры: *, +, -, например:
* Первый
+ Второй
- Третий

Вложенный список: 4 пробела или таб перед маркером, например:
1. Первый
2. Второй
    * Третий
    * Четверытй
        + Пятый
        + Шестой
            - Седьмой
            - Восьмой
___
# *Оформление цитаты*

>Природа никогда не спешит, но всегда успевает.
>
> *- Лао-Цзы*
___
# *Оформление картинки*

![Лао Цзы](lao-czy.jpg)
___
# *Оформление ссылки*

[Цитаты известных личностей](https://ru.citaty.net/tsitaty/616703-lao-tszy-priroda-nikogda-ne-speshit-no-vsegda-uspevaet "Лао Цзы")
___
___
Тестовый текст
+ +1
    - +2

Test text
* -1
    + -2
        * -3

***Go!*** 
___

Заметки:

1. Заметки пишу в ветке "notes".
2. Конфликт после слияния ветки "edits" с веткой "master" решил, оставив оба варианта.
3. Добавлен файл .gitignore для не отслеживания git_Скрин с конфликтом.png. 
4. Буду создавать еще одну ветку с пустой инструкцией для "git log --graph" 
       
