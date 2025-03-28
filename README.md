## Повышение отказоустойчивости приложения, кеширование, мониторинг, логирование, трейсинг, метрики производительности

### Архитектура приложения
[<img src="Ex1/pictures/architecture.png" width="1200"/>](Ex1/pictures/architecture.png)

Распределенная система состоит из следующих приложений:     
- Shop  
  - приложение для заказов(фронт JS-Vue, бек Java-Spring);   
- CRM(Customer Relationship Management)  
  - spa(single page application) приложение для работы с клиентами(фронт JS-Vue, бек Java-Spring);  
- MES(Manufacturing Execution System)  
    - spa-приложение для управления производственными процессами, включая расчет стоимости производства(фронт JS-React, бек C#-Asp.Net);  

CRM и MES взаимодействуют друг с другом через брокер RabbitMQ.  

С ростом нагрузки снижается производительность распределенной системы.  

Для выявления проблемных мест в распределенной системе применяются сбор данных о ее работе посредством
мониторинга, логирования и трейсинга.   

В целях повышения отказоустойчивости приложения применяется кеширование.    

## [Анализ, идентификация проблем и решений, планирование изменения архитектуры](Ex1/Анализ_проблем.md)    
## [Мониторинг](Ex2/Мониторинг.md)    
## [Трейсинг](Ex3/Трейсинг.md)    
## [Логирование](Ex4/Логирование.md)    
## [Кеширование](Ex5/Кеширование.md)    

