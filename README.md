# ELK
## Домашнее задание к занятию «ELK»

## Задание 1. Elasticsearch
Установила и запустила Elasticsearch, изменила `cluster_name` на `my-cool-cluster`.  
Выполнила запрос `curl -X GET 'localhost:9200/_cluster/health?pretty'` и получила ответ:

![Cluster health](images/task1.png)

## Задание 2. Kibana
Установила и запустила Kibana. В интерфейсе Dev Tools выполнила запрос `GET /_cluster/health?pretty`:

![Kibana Dev Tools](images/task2.png)

## Задание 3. Logstash

Настроила Logstash для сбора access-логов Nginx и отправки в Elasticsearch.  
Логи Nginx отображаются в Kibana (индекс `nginx-access-*`):

![Nginx логи через Logstash](images/task3.png)
## Задание 4.  Filebeat

## Задание 5*. Доставка данных
