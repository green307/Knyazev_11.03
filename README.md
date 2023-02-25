# Домашнее задание к занятию 11.3. «ELK»


Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.




![alt text](https://github.com/green307/Knyazev_11.03/blob/7abaff27c20b00344df2e5e958080185fc20a474/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B51.jpg)



Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.




![alt text](https://github.com/green307/Knyazev_11.03/blob/7abaff27c20b00344df2e5e958080185fc20a474/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B52.jpg)



Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

![alt text](https://github.com/green307/Knyazev_11.03/blob/7abaff27c20b00344df2e5e958080185fc20a474/%D0%97%D0%B0%D0%B43.jpg)



Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.


![alt text](https://github.com/green307/Knyazev_11.03/blob/7abaff27c20b00344df2e5e958080185fc20a474/%D0%97%D0%B0%D0%B44.jpg)
