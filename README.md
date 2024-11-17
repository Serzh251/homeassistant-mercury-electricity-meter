# homeassistant-mercury-electricity-meter
Интеграция для опроса счетчиков меркурий в homeassistant

## Тестирование проводилось на счетчике:
 - меркурий 230 ART-02 PQC(R)SIN(6)

## Подключение
Подключение осуществляется через RS-485 протокол, согласно инструкции к счетчику. Использовался Usb-RS485 переходник
для подлключения и Rasberry Pi4 8GB с установленным Home Assistant Supervised

Пример настройки указан в __configuration.yml__
При использовании всех сенсоров указанных для примера, период опроса в 60сек обычно достаточен, но зависит от
системы и колличества используюемых сенсоров.

В проекте могут быть не точности, возможны правки.
