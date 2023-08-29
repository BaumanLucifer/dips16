# Само задание доступно по ссылке:
## [SYS-DIPLOM](https://github.com/netology-code/sys-diplom)

Ждем создания инфраструктуры

![1](https://github.com/BaumanLucifer/dips16/blob/master/img/1.PNG)

**Список ВМ (test1 - машина с дипломом)**:

![2](https://github.com/BaumanLucifer/dips16/blob/master/img/2.PNG)

![3](https://github.com/BaumanLucifer/dips16/blob/master/img/3.PNG)

**VPC (стандартную решил не показывать)**

![4](https://github.com/BaumanLucifer/dips16/blob/master/img/4.PNG)

**Группы безопасности**:

![5](https://github.com/BaumanLucifer/dips16/blob/master/img/5.PNG)

**inventory.ini**:

![6](https://github.com/BaumanLucifer/dips16/blob/master/img/6.PNG)


**Пингую сервера ансиблом**:

![7](https://github.com/BaumanLucifer/dips16/blob/master/img/7.PNG)

**Установка elasticsearch**:

![8](https://github.com/BaumanLucifer/dips16/blob/master/img/8.PNG)

**Установка filebeat**:

![9](https://github.com/BaumanLucifer/dips16/blob/master/img/9.PNG)

**Установка kibana**:

![10](https://github.com/BaumanLucifer/dips16/blob/master/img/10.PNG)

**Установка nginx**:

![11](https://github.com/BaumanLucifer/dips16/blob/master/img/11.PNG)

**Установка log-exporter**:

![12](https://github.com/BaumanLucifer/dips16/blob/master/img/12.PNG)

**Установка node-exporter**:

![13](https://github.com/BaumanLucifer/dips16/blob/master/img/13.PNG)

**Установка prometheus**:

![14](https://github.com/BaumanLucifer/dips16/blob/master/img/14.PNG)

**Установка grafana**:

![15](https://github.com/BaumanLucifer/dips16/blob/master/img/15.PNG)

Затем захожу на сайт графаны по адресу

``http://51.250.37.23:3000
``

Пароль и логин **admin:admin**


![16](https://github.com/BaumanLucifer/dips16/blob/master/img/16.PNG)

**Проверяем балансировщик и что сервера HEALTHY**:

![17](https://github.com/BaumanLucifer/dips16/blob/master/img/17.PNG)

Затем захожу на **kibana** по адресу:

``http://51.250.45.238:5601
``

Видим, что взаимодействие с файлбитом есть. Логи собираются.

![18](https://github.com/BaumanLucifer/dips16/blob/master/img/18.PNG)

Создаю расписание для снимков 

![19](https://github.com/BaumanLucifer/dips16/blob/master/img/19.PNG)

![20](https://github.com/BaumanLucifer/dips16/blob/master/img/20%20%D0%A1%D0%BD%D0%B8%D0%BC%D0%BA%D0%B8%20%D0%B4%D0%B8%D1%81%D0%BA%D0%BE%D0%B2.PNG)

**Работа выполнена**
