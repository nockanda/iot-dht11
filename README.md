# iot-dht11
Check the temperature and humidity on your smartphone using Arduino and dht11 sensor!

![501-3_bb](https://user-images.githubusercontent.com/106683637/175526014-8eba2bde-ac42-4c40-9297-b6ece700379a.jpg)

This is the schematic of the project! The left one is when you upload the program and the right one is when you use it!
This code requires the dht11 1.3.8 version library!

Below is an explanation video! Sorry, it's in Korean!

[![Video Label](http://img.youtube.com/vi/ymv_vlTrJJE/0.jpg)](https://youtu.be/ymv_vlTrJJE)

1. Connect dht11 to wemos d1 mini board.
2. Connect the battery to the wemos d1 mini board.
3. Connect the reset button and the setting button.
4. If you press the reset button while holding down the setting button, the iot board operates in AP mode.
5. You can edit Internet router information and mqtt information in setting mode.(Information updated in AP mode is saved using spiffs.)
6. In normal mode, temperature and humidity values are transmitted by MQTT.
7. Deep sleep mode when not transmitting!(Consumes 4.4mA current)
8. Check on your smartphone!
