# Вера Никитинская, S4107

Задания - 2 семестр, весна 2018

## 09/02/2018
JS

- [Крамер](0902/kramer.js)
- [Тернарный оператор](0902/ternary1.js)
- [isNaN](0902/isnan.js)
- [Полнота](0902/jsfck.js)
- Get bytecode:

    use flags, e.g
    ```bash
    node --print_code -e 'console.log("hello")'
    ```
    (optimized machine code generated by TurboFan compiler)

    or
    ```bash
    node --print_bytecode -e 'console.log("hello")'
    ```
    (bytecode)
- Undefined vs not defined:

    In node, `node -e` only evaluates, while `node -p` evaluates and prints result, and the returned result includes the implicitly returned undefined.

    Undefined means the variable exists, but isn't given a value yet.
    Not defined variables don't exist yet in the current lexical environment, that is, are not accessible there or weren't yet created.

PHP
- [Крамер](0902/kramer.php)
- [Тернарный оператор](0902/ternary.php)
- [isNAN](0902/isnan.php)

## 16/02/2018
- [diff2html](1602/part1/)
- [Замыкания](1602/part4/)


## 02/03/2018
- Часть 1

  [Тренинг по массивам](https://codepen.io/nikitinskaya/pen/XEKxWp)
- Часть 2 - сборка и транспиляция

[Код](0203/)

Демо:
  - [Задание 1](http://nikitinskaya.me/gossjs-sem2/0203/task1)
  - Задание 2
    - [Часть 1](http://nikitinskaya.me/gossjs-sem2/0203/task2/part1)
    - [Часть 2](http://nikitinskaya.me/gossjs-sem2/0203/task2/part2)
  - [Задание 3](http://nikitinskaya.me/gossjs-sem2/0203/task3)

## 30/03/2018
- [Асинхронные задания](https://codepen.io/nikitinskaya/pen/EEEwOZ)
- [Приложение на Silex](https://github.com/nikitinskaya/silex-app-sem2)
