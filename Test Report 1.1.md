# Отчет о тестировании KeyValidator.class

## Краткое описание
13/07/2020 – 13/07/2020 было проведено функциональное тестирование приложения «KeyValidator».

На тестирование затрачено: 1,5 часа

В результате тестирования выявлены следующие дефекты:

* [Bug Issue 1](https://github.com/Anastasia-Rybak-2044/Java-Hometask-1.1/issues/4)
* [Bug Issue 2](https://github.com/Anastasia-Rybak-2044/Java-Hometask-1.1/issues/5)
* [Bug Issue 3](https://github.com/Anastasia-Rybak-2044/Java-Hometask-1.1/issues/6)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Инструкция по установке OpenJDK 11
https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md
* Руководство использования KeyValidator
https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md

В качестве тестовых данных использовались: 

* Данные из руководства использования KeyValidator:
https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md:

Валидные ключи:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

## Тестирование производилось в следующем окружении:

* Ноутбук: HP-Pavilion-Gaming-Laptop-15
* ОС: Linux Mint 19.3 x 64
* Версия Java: openjdk 11.0.7 2020-04-14
* Браузер: Google Chrome
