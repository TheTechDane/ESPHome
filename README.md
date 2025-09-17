# YAML Collection.

Just a collection of ESPHome samples that shows how different parts is working, feel free to use what you can , but no support on this repository.. ideas are welcome 


## ESP32C3 - OLED 0.42:
Important to know the display is 72x40, ESPHome at present time (2025 Feb." does not have a 72x40 so use the 128x64 and offset with 28)[Display Docs.](https://esphome.io/components/display/)

![ESP32-C3 OLED](images/esp32c3-oled.png)![](../images/esp32c3-oled-local-IP_300x400.jpg
)

[AliExpress](https://www.aliexpress.com/item/1005007342383107.html?spm=a2g0o.order_list.order_list_main.181.21ef79d2pBUubG)

[YAML Test File](<Misc. YAML files/small-display-test.yaml>)

## OLED 0.96
Larger display easer to work with.. [Display Docs.](https://esphome.io/components/display/)

![0.96 OLED](images/esp32-c3%20-%20oled%200.9_300x400.jpg)

[YAML Test File](<Misc. YAML files/esphome-0.94%20SSD1303%20Display.yaml>)

## Led strip 
Led strips - I normally use WLED, it is really flexable and has allot of extra functionality, but if you have to use the ESP32 for more that LED Strips, EXPHome offers alot od functionality that can be added on a ESP32 that is used for sensors or Display driver. [esp32_rmt_led_strip Docs](https://esphome.io/components/light/esp32_rmt_led_strip)

![alt text](<images/Breadboard-light strip.png>)

The default dashboard cart only have a on and foo switch, in order to have more functions exposed on the Dashboard for the LightStrip use the Custom [light-entety-card](https://github.com/ljmerza/light-entity-card) that is available in the HACS store. 

![](images/custom-light-card.png)

[YAML File](<Misc. YAML files/esphome-Light-strip.yaml>)

## Single LED or LED Filiment
If you need to control a single LED you could use the [Status LED light](https://esphome.io/components/light/status_led.html) but it only controls on and off - Not brightness. Instead use [LEDC Output](https://esphome.io/components/output/ledc) 
The LED filement used here is from Ali express and uses 3Volts same as the pin output.

![setup](images/led-filament.png)![poliazation](images/Led-filement-polaization.png)

[Ali Express](https://www.aliexpress.com/item/1005007294507470.html?spm=a2g0o.order_list.order_list_main.89.7ae279d2L82cOK)

[YAML File](<Misc. YAML files/esphome-Single LED.yaml>)

## Lilygo S3 Long
Firste test of a S3 Long Touch Display - I am working on a ESPHome project as a StreamDeck kind a device.
![Setup](<images/LilygoS3First go.jpg>)

[3D Case](https://makerworld.com/en/models/1070855-lilygo-t-deisplay-s3-long-case-w-stand#profileId-1060745)


[YAML File](<Misc. YAML files/esphome-Lilygo-S3-Long - New first version fixed.yaml>)




