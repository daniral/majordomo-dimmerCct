# majordomo-dimmerCct
Управление освещением с возможностью изменения яркости и теплоты.

Simple Devices addon (Xiaomi ZigBee light)
Поддерживаются метрики (status +bright +cct)

An add-on that adds a new type of device (Xiaomi ZigBee Lamp).
After creating a simple device, you need to bind the brightness of the lamp to the brightLevelWork property, the temperature to the cctLevelWork property, and the status to the status property.
In the settings of the simple device, set the min/max working level of brightness and temperature (For example, for a Xiaomi lamp, the brightness is from 0 to 254. 0 - turns off. Temperature from 153 (white) to 370 (yellow)).
After that, we write in the properties brightLevel (brightness) and cctLevel (temperature) as a percentage from 0 to 100.

Дополнение, которое добавляет новый тип устройства (Xiaomi ZigBee Lamp).
После создания простого устройства надо привязать яркость лампы к свойству brightLevelWork, температуру к свойству cctLevelWork, состояние к свойству status.
В настройках простого устройства установить мин/макс рабочий уровень яркости и температуры(Например для лампы Xiaomi яркость от 0 до 254. 0 - выключит. Температура от 153(белый) до 370(жёлтый)).
После этого пишем в свойства brightLevel(яркость) и cctLevel(температура) в процентах от 0 до 100.


* Голосовые команды:
1. включи|зажги "название ПУ"
2. выключи|потуши|отключи "название ПУ"
3. включи|зажги "название ПУ" "число" секунд|минут|часов
4. выключи|потуши|отключи "название ПУ" "число" секунд|минут|часов
5. яркость|ярче "название ПУ" "число"
6. температур|температура|цвет|теплота "название ПУ" "число"