# Лабораторная работа №6
Настройка безопасности STP


## Часть 1 Конфигурирование основных настроек устройств
 
1.	Топология

![alt-текст][Топология]

[Топология]:https://github.com/b00mmer/Lab6/blob/main/Topology.JPG "Топология"

2. Таблица адресации

![alt-текст][Таблица]

[Таблица]:https://github.com/b00mmer/Lab6/blob/main/%D0%A2%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0%20%D0%B0%D0%B4%D1%80%D0%B5%D1%81%D0%BE%D0%B2.JPG "Таблица адресации"

3. [Сетевые параметры маршрутизатора R1](https://github.com/b00mmer/Lab5/blob/main/R1_running-config.txt)
4. [Сетевые параметры маршрутизатора R2](https://github.com/b00mmer/lab5/blob/main/R2_running-config.txt)
5. [Сетевые параметры маршрутизатора R3](https://github.com/b00mmer/Lab5/blob/main/R3_running-config_3.txt)
6.  [Сетевые параметры Server0 PC-A](https://github.com/b00mmer/Lab5/blob/main/server0.JPG)
6.  [Сетевые параметры PC-B](https://github.com/b00mmer/Lab5/blob/main/PC-B.JPG)
7.  [Сетевые параметры PC-C](https://github.com/b00mmer/Lab5/blob/main/PC-C.JPG)
 

 ## Часть 2 Настройка файервола на основе зонных политик на R3

 [Сетевые параметры маршрутизатора R3](https://github.com/b00mmer/Lab5/blob/main/R3_running-config.4.txt)
  
  ## Часть 3 Проверка функциональности файервола на основе зонных политик на R3

1. Трафик, исходящий из Интернета  

Проверка с SERVER 0

![alt-текст][Internet]

[Internet]:https://github.com/b00mmer/Lab5/blob/main/Ping-A.JPG "Internet"

Протокол ICMP не разрешен на файерволе.

Проверка с PC-B

![alt-текст][INSIDE]

[INSIDE]:https://github.com/b00mmer/Lab5/blob/main/Ping-B.JPG "INSIDE"


![alt-текст][HTTP]

[HTTP]:https://github.com/b00mmer/Lab5/blob/main/PC-C-web.JPG "HTTP"



![alt-текст][HTTPS]

[HTTPS]:https://github.com/b00mmer/Lab5/blob/main/PC-C-webs.JPG "HTTPS"




Проверка с PC-C

![alt-текст][CONFROOM]

[CONFROOM]:https://github.com/b00mmer/Lab5/blob/main/Ping-C.JPG "CONFROOM"


Протокол ICMP не разрешен на файерволе.

2. Самостоятельная проверка зоны


![alt-текст][SELF1]

[SELF1]:https://github.com/b00mmer/Lab5/blob/main/Ping-A-R.JPG "SELF1"


![alt-текст][SELF2]

[SELF2]:https://github.com/b00mmer/Lab5/blob/main/Ping-C-R.JPG "SELF2"


## Приложение

![alt-текст][Appen]

[Appen]:https://github.com/b00mmer/Lab5/blob/main/Appen.JPG "Appen"

