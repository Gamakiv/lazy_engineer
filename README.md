Lazy_engineer
=============================
Ввод пароля с помощью Teensy 2.0, которая сопряжена с Arduino UNO по I2C. 
UNO считывает карту, если карта верна звучит короткий звуковой сигнал и передается сигнал о вводе на Teensy.
Если карта не верна, то звучит длинный звуковой сигнал.

Информация о плате Teensy 2.0 (https://www.pjrc.com/store/teensy.html)
Для прошивки платы, потребуется Teensyduino (https://www.pjrc.com/teensy/td_download.html)

TODO
------------

* Удаленные команды с помощью IR или bluetooth
* Автокликер
* Дисплей с информацией о аптайме, количество произведенных вводов


PS
------------
Да, плата teensy не самая новая и популярная, но под рукой не было чего то поновее и что умеет эмуляцию HID.
Все это можно соорудить на Arduino Nano
