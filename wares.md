## Прошивки

### [QMK](https://github.com/oleg-rnd/rogwiki/tree/main/Firmwares/QMK.md)  
наиболее известная и часто используемая прошивка  
[GitHub](https://github.com/jackhumbert/qmk_firmware) 

### TMK
предшественница QMK  
[GitHub](https://github.com/tmk/tmk_core)

### [Keyberon](https://github.com/TeXitoi/keyberon)  
альтернативная прошивка, созданная на языке Rast
[GitHub](https://github.com/TeXitoi/keyberon) 

### [Easy AVR](https://deskthority.net/wiki/Easy_AVR_USB_Keyboard_Firmware)  
графический интерфейс для создания раскладок для самодельных клавиатур  

## Конторллеры

Основной архитектурой для QMK/TMK является AVR:  

- ATmega32U4 (PJRC Teensy 2.0, Pro Micro).
- AT90USB1286 (PJRC Teensy++ 2.0)
- ATmega168P и ATmega328P поддерживаются, но из-за отсутствия аппаратного USB-стека требуют V-USB.
- ATmega32U2

Некоторое время назад была добавлена поддержка ARM-микроконтроллеров, совместимых с ChibiOS. Наиболее распространённые и проверенные: Blue Pill, Black Pill, Teensy LC, Teensy 3.2. Поддержка ARM/ChibiOS развивается медленно, работает не весь функционал: Bootmagic, звук и т. д.


Краткое [описание используемых **контроллеров**](https://github.com/Flumeded/ru_mech/blob/master/docs/QMK.md#Контроллеры)  
  
