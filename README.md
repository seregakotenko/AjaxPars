AjaxPars.php
========
![PHP version](https://img.shields.io/badge/PHP->=v5.6-green.svg?php=5.6)    [![GitHub release](https://img.shields.io/badge/releases-1.1.4-blue.svg)](https://github.com/indeximstudio/AjaxPars/releases)

Класс для создания переборов любых данных посредством ajax c лёгкой реализацией.


## Публичные Методы
### getScript()
@return string

подключает скрипты к странице

### getProgress()
@return string

вывод полосы прогресса

### StartPars()
запуск перебора

### StopPars()
остановка перебора

### getValueJson()
@return string (json)

возвращает информацию о выполненом запросе на страницу в формате json



## Абстрактные методы

### getCountIterations()
@return int

возвращает количество элементов перебора

### getAction()
выполнение действий c полученными данными

