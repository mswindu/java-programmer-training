# Конфигурирование embedded tomcat в Spring

Цель задачи состоит в том, чтобы начинающие разработчики избежали распространненой ошибки - использование настроек tomcat по умолчанию в Spring.

Шаги выполнения:
1. Создать WEB-приложение на основе spring boot. 
2. Реализовать несколько endpoint, которые возвращают ОК. Внутри этих методов поставить sleep 0.1с, 0.5с, 1.0с.
3. Используя JMeter посмотреть текущие возможности приложения.
4. Изучить и изменить настройки embedded tomcat. Посмотреть как изменятся результаты в JMeter.

Полезные ссылки:
1. [How To Do Performance Testing for the Java API with JMeter](https://medium.com/bb-tutorials-and-thoughts/how-to-do-performance-testing-for-the-java-api-with-jmeter-e72e163f4e7c)