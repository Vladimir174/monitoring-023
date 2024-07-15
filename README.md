# monitoring-023
Beats - инструменты доставки данных // ДЗ 

Установка и настройка отправки данных с помощью Beats

Цель:
Научиться отправлять логи, метрики с помощью beats в elasticsearch.

1. На виртуальной машине установите любую open source CMS, которая включает в себя следующие компоненты: nginx, php-fpm, database (MySQL or Postgresql). Можно взять из предыдущих заданий;
2. На этой же VM установите filebeat и metricbeat. Filebeat должен собирать логи nginx, php-fpm и базы данных. Metricbeat должен собирать метрики VM, nginx, базы данных;
3. Установите на второй VM Elasticsearch и kibana, а также heartbeat; Heartbeat должен проверять доступность следующих ресурсов: веб адрес вашей CMS и порта БД


  **Установлены filebeat и metricbeat**. Конфиги: 
  
  filebeat - https://github.com/Vladimir174/monitoring-023/blob/main/filebeat.yml

  
  metricbeat - https://github.com/Vladimir174/monitoring-023/tree/main/metricbeat

  
  Heartbeat - 
   ![image](https://github.com/user-attachments/assets/ffb25da6-8953-4143-8fc1-3e2f11e10a0d)

   **filebeat cобирает логи nginx, php-fpm и БД.**
   

   ![image](https://github.com/user-attachments/assets/cceb9bd0-53d7-41bf-8c9d-09cca5dbf022)

   ![image](https://github.com/user-attachments/assets/906b9eb3-5f39-448e-b990-23f8add87b4f)

   ![image](https://github.com/user-attachments/assets/24ac1f1c-fd41-4109-9449-8a7ccdf5ad98)



   ![image](https://github.com/user-attachments/assets/5ede0a74-d0ee-4b8c-8301-9e0c6385989e)


**Metricbeat собирает метрики VM, nginx, базы данных;**


![image](https://github.com/user-attachments/assets/2595056f-6787-4adb-904a-ac60d5358edd)



**Heartbeat проверяет доступность следующих ресурсов: веб адрес CMS и порта БД**


![image](https://github.com/user-attachments/assets/508022f3-b172-4eeb-aeeb-afae42abf14f)

**Мониторы**

![image](https://github.com/user-attachments/assets/46335801-f861-486d-901f-a1990d1bf3a0)









