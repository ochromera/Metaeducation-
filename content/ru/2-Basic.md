# 2. Базовые концепты

Нам нужны комментарии для временного предотвращения выполнения или компиляции блока кода, для хранения структурированных аннотаций или метаданных (интерпретируемых специальными инструментами), для добавления TODO или понятных разработчику объяснений.

> Комментарий — это последовательность символов в коде, игнорируемая компилятором или интерпретатором.

Комментарии во всех языках семейства `C`, таких как `C++`, `JavaScript`, `Java`, `C#`, `Swift`, `Kotlin`, `Go` и т. д., имеют одинаковый синтаксис.

```js
// Single-line comment
```

```js
/*
  Multi-line
  comments
*/
```

Не держите в комментариях очевидные вещи, не повторяйте то, что и так понятно из самого кода.

В `bash` (shell-скриптах) и `Python` мы используем знак "номер" (диез или решётку) для комментированиев.

```py
# Single-line comment
```

`Python` использует многострочные строки как многострочных комментариев с выделение тройными кавычками. Но помните, что это строковый литерал, не присвоенный в переменную.

```py
"""
  Multi-line
  comments
"""
```

SQL использует два тире, чтобы начать однострочный комментарий до конца строки.

```sql
select name from PERSON -- comments in sql
```

HTML-комментарии имеют только многострочный синтаксис.

```html
<!-- commented block in xml and html -->
```

В ассемблере и множестве диалектов LISP мы используем точку с запятой (или несколько точек с запятой) для различных типов комментариев.

```
; Single-line comment in Assembler and LISP
```
