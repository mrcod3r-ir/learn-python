# Topics :

**Lecture 1**

- intro
- syntax
- comments
- variables intro
- keywords intro
- data types
- number intro
- string intro
- boolean intro
- collections intro
- list intro
- dictionary intro
- operators
- if-else intro
- while loops intro
- break / continue

**Lecture 2**

- for loops intro
- functions intro
- variables 2
- number methods 1
- string methods 1
- boolean methods 1
- list methods 1
- dictionary methods 1
- if-elif-else

**lecture 3**

- while loops : else/pass
- dictionary methods 2 : nested dictionary
- for loops 2 : nested/range/pass/else
- functions 2
- exceptions
- try/except
- tuples intro
- sets intro

**Lecture 4**

- number methods 2
- string methods 2
- boolean methods 2
- list methods 2
- dictionary methods 2
- files
- keywords 2
- lambda

**Lecture 5**

- modules
- os
- csv

# Sub Topics

- **_intro_**

  - intro

    - Python is a **_high-level_**, general-purpose programming language (**_GPL_**).
    - Its design philosophy emphasizes code readability with the use of significant indentation.

  - used for ?
    - web development (server-side),
    - software development,
    - mathematics,
    - system scripting.
  - what can python do?
    - Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
    - Python has a simple syntax similar to the English language.
    - Python has syntax that allows developers to write programs with fewer lines than some other programming languages.
    - Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
    - Python can be treated in a procedural way, an object-oriented way or a functional way.
  - why python ?

- **_syntax_**

  - Execute Python
  - Indentation

- **_comments_**

  - single line comment
  - multi line comment

- **_variables intro_**
  - create var
  - print()
  - casting
    - str()
    - int()
    - float()
  - Quotes
  - Case Sensitive
  - var names rules
    - must start with (A-z, 0-9, and \_ )
    - cannot start with a number
    - can only contain (A-z, 0-9, and \_ )
    - are case-sensitive (hero,Hero,HERO)
    - typing cases
      - camelCase ✓
      - PascalCase ✓
      - snake_case ✓
      - kebab-case x
    - cannot be any of the Python keywords.
- **_keywords intro_**
  - if elif else
  - True False
  - def del
- **_data types_**

  - types :
    - Text : `str`
    - Numeric : `int, float, complex`
    - sequence : `list, tuple, range`
    - Mapping : `dict`
    - Set : `set, frozenset`
    - Boolean : `bool`
    - Binary : `bytes, bytearray, memoryview`
    - None : `NoneType`
  - get type : `type()`
  - set type
    - assign
    - constructor

- **_number intro_**

  - int
  - float

- **_string intro_**

  - length: `len()`
  - check : `in`
  - check : `not in`
  - upper case : `upper()`
  - lower case : `lower()`
  - split : `split()`
  - concatenation : `a+b a+" "+b`
  - format
    - can't combine to number : `str+num`
    - format()
    - f
  - escapes
    - \
    - \n
    - \t

- **_boolean intro_**

  - `True False`
  - `bool()`

- **_list intro_**

  - list `['x','y','z']`
  - items `[0]`
  - ordered
  - changeable
  - allow duplicates
  - length `len()`
  - type `type()`

- **_collections intro_**

  - List
  - Dictionary
  - Tuple
  - Set

- **_list intro_**

  - `list[0]` , `list[-1]`
  - range of list `list[2:5] list[:3] list[2:]`
  - check if `if "apple" in list`
  - change list `list[1] = "some"`
  - change range of list `list[1:2] = ["some","do"]`
  - insert `list.insert(2,"some")`
  - append `list.append("end")`
  - extend `listOne.extend(listTwo)`
  - remove `list.remove("some")`

- **_dictionary intro_**

  - syntax :

  ```
  hero = {
    "firstName" : "Mostafa",
    "lastName" : "Ahmadi Roshan",
    "age":32,
    "martyrdomDate":"1390-10-21"
  }
  ```
