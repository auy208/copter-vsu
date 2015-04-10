# Introduction #

Техническая информация


# Details #

29/11/2014


Стартовая информация по элементам

1.Примеры расширения для ардуины с датчиками. Общий вид http://aeroquad.com/showthread.php?951-AeroQuad-v1.8-Shield&p=9303

Процесс сборки и установки оборудования http://aeroquad.com/showwiki.php?title=Hardware%20Assembly%20v2%201%202%202%20Shield&redirect=no

Установка инерциальных датчиков ""

2.Информация по MPU6050. http://playground.arduino.cc/Main/MPU-6050

Статья с рабочим примером http://www.geekmomprojects.com/gyroscopes-and-accelerometers-on-a-chip/

На русском языке http://robot-kit.ru/product_info.php/info/p587_Modul-GY-521-yeto-trehosnyi-akselerometr-i-3-h-osevoi-giroskop-dlya-Arduino-na-mikrosheme-MPU-6050--Module-3-Axis-Gyroscope-and-Accelerometer-for-Arduino--RKP-GY-521-MPU6050-.html

Другой модуль, но пусть будет http://www.instructables.com/id/Guide-to-gyro-and-accelerometer-with-Arduino-inclu/

Может поможет, может нет, а вдруг, но русском языке http://arduino.ru/forum/apparatnye-voprosy/giroskop-gy-521-na-osnove-mpu-6050

3. Информация по PID регулятору. Статья с конкретным примером http://brettbeauregard.com/blog/2011/04/improving-the-beginners-pid-introduction/

Библиотека для arduino http://playground.arduino.cc/Code/PIDLibrary

4. Соответствие выводов платы aeroquad и arduino

AeroQuad?(v 1.8) -> Arduino UNO

Мотор1 (или серво трикоптера)-> D3

Мотор2 -> D9

Мотор3 -> D10

Мотор4 -> D11

Приемник (PWM) -> Arduino UNO

Roll-> D2

Throttle-> D4

Pitch -> D5

Yaw -> D6

Mode -> D7

Aux1 -> D8


AeroQuad(v 2.0) -> Arduino MEGA

Мотор1 (или серво трикоптера)-> D2

Мотор2 -> D3

Мотор3 -> D5

Мотор4 -> D6

Приемник (PWM) -> Arduino MEGA

Roll-> A9

Throttle-> A8

Pitch -> A10

Yaw -> A11

Mode -> A12



Чтобы работало, необходимо убрать комментарий у строчки #include <Receiver\_328p.h>



---

07/12/2014

MPU6050

DataSheet
http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Components/General%20IC/PS-MPU-6000A.pdf

Register map

http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Sensors/Accelerometers/RM-MPU-6000A.pdf


---

04.01.2015

Информация по фильтрам

http://www.starlino.com/dcm_tutorial.html

http://www.rossprogrammproduct.com/translations/Matrix%20and%20Quaternion%20FAQ.htm


---

17/01/2015

По навигации

http://keldysh.ru/papers/2013/prep2013_39.pdf

Стр.13 определение углов Крылова (самолетных) по компонентам кватерниона


---

22.01.2015

AeroQuad и mpu6050

http://www.youtube.com/watch?v=zDde6YCixm4


---


10.04.2015

[Ultrasonic Ranging Module HC-SR04 Datasheet](http://www.micropik.com/PDF/HCSR04.pdf)

[Radio Data Module http://www.dfrobot.com/wiki/index.php/APC220\_Radio\_Data\_Module(SKU:TEL0005)](APC220.md)

[Datasheet http://www.dfrobot.com/image/data/TEL0005/APC220\_Datasheet.pdf](APC220.md)