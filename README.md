# 932021.Zamyatin.Alexander.Lab11

Лабораторная работа №11 по предмету Web-технологии Цель работы: Вывод данных на Web-страницу

Цель работы: Разработка Web-приложения по предоставленному техническому заданию.
Описание:
•	Создание минимального Web-приложения на ASP.NET Core с нуля.
•	Работа с контроллерами и представлениями.
•	Передача данных из контроллера в представление с помощью модели представления.
•	Передача данных из контроллера в представление с помощью ViewBag.

Задание: Для двух случайных чисел в диапазоне от 0 до 10 необходимо реализовать сервис для выполнения 4 базовых операций (сложение, вычитание, умножение, деление). Необходимо предусмотреть обработку ошибок (деление на ноль).


# Requirements
- PHP 8.2
- Composer
- Docker

# How to install
1) Установить composer по инструкции с официального сайта: https://getcomposer.org/download/
2) Установить docker по инструкции с официального сайта: https://docs.docker.com/engine/install/
3) Открыть докер и дождаться его запуска, должно открыться следующее окно:
![image](https://github.com/Wantedfoxy/932021.Zamyatin.Alexander.Lab11/assets/50704060/d65b64b0-11af-466b-b850-5a5f0f587379)
4) Склонировать данный репозиторий через консоль, предварительно убедитесь, что вами выбрана верня директория <br>
(`git clone https://github.com/Wantedfoxy/932021.Zamyatin.Alexander.Lab11.git`)
5) `cd 932021.Zamyatin.Alexander.Lab11`
6) `composer update`
7) `composer install`
8) `docker compose up --build -d`
9) Открыть `http://localhost:2003`
