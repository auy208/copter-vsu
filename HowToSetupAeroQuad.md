# Introduction #

Рассмотрим, как запустить и настроить программу AeroQuad на Arduino Mega.


# Details #

Подробное описание по шагам: http://aeroquad.com/showwiki.php?title=Book:Arduino-based+boards

Скачать исходный код AeroQuad: https://github.com/AeroQuad/AeroQuad

Скачать AeroQuad Configurator: http://code.google.com/p/aeroquad/downloads/list

Загрузить AeroQuad в контроллер: http://aeroquad.com/showwiki.php?title=Uploading+via+the+Arduino+IDE

-

[Ссылка на исходные файлы AeroQuad, которые я правил.](https://drive.google.com/folderview?id=0B3lziualhjDtajRIQWhQTmNIelk&usp=sharing)

Для использования гироакселерометра [MPU6050](http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Components/General%20IC/PS-MPU-6000A.pdf) необходимо внести изменения в код. [Видео, как это сделать](http://www.youtube.com/watch?v=zDde6YCixm4)

Добавление initializeMPU6000Sensors() в функцию initPlatform и readMPU6000Sensors() в measureCriticalSensors, как показано в видео, на самом деле не требуется, они и так вызываются - проверено.

-

Подключение приёмника (receiver) и регуляторов хода (ESC):


чёрный/коричневый - минус,

красный - плюс,

белый/жёлтый - сигнал

[РАСПИНОВКА](https://docs.google.com/spreadsheet/ccc?key=0AoZ5bZF0qNerdDBPdjQ5cm1GU2Y0ZHBxa2FaZmVYeVE&authkey=CJP8mtsF&hl=en&authkey=CJP8mtsF#gid=0)

[Ещё распиновка](http://aeroquad.com/showthread.php?6341-allanGEE-s-Second-Quadcopter&p=56331&viewfull=1#post56331)

-

Ориентация MPU6050:
Z - Down,
X - Front,
Y - Right,