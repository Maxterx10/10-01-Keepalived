# Домашнее задание к занятию "`10.1. Keepalived/vrrp`" - `Белов Максим`


### Задание 1

Статус keepalived сразу после запуска (master на второй ноде, так как интерфейс на первой был выключен):

![alt text](https://github.com/Maxterx10/10-01-Keepalived/blob/main/10-01-1.1.png)

Интерфейсы сразу после запуска keepalived:

![alt text](https://github.com/Maxterx10/10-01-Keepalived/blob/main/10-01-1.2.png)

Отключаю интерфейс на второй ноде и виртуальный ip перемещается на первую ноду:

![alt text](https://github.com/Maxterx10/10-01-Keepalived/blob/main/10-01-1.3.png)

Статус keepalived после отключения интерейса на второй ноде:

![alt text](https://github.com/Maxterx10/10-01-Keepalived/blob/main/10-01-1.4.png)

Статус keepalived после включения интерфейса на второй ноде:

![alt text](https://github.com/Maxterx10/10-01-Keepalived/blob/main/10-01-1.5.png)

Конфиг:

![alt text](https://github.com/Maxterx10/10-01-Keepalived/blob/main/10-01-1.6.png)

Единственное: если выключить интерфейс на мастер-ноде и заново включить - то мастер не вернется на мастер-ноду, а останется на второй ноде.

---

### Задание 2

![alt text](https://github.com/Maxterx10/10-01-Keepalived/blob/main/10-01-2.1.png)
![alt text](https://github.com/Maxterx10/10-01-Keepalived/blob/main/10-01-2.2.png)
