Garage door project to convert my Liftmaster MyQ opener to local only operation. They have had a few outages over the past year and I also think it is quite silly to send some things to/from cloud services.

**ESP32 + Relay + Opener PCB + Ultrasonic Sensor**

Component list:
[ESP32](https://www.amazon.com/gp/product/B07BK435ZW/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
Relay - https://www.amazon.com/gp/product/B0798CZDR9/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1
Ultrasonic - https://www.amazon.com/gp/product/B01JG09DCK/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1
Project box - https://www.amazon.com/gp/product/B08PP1W8Q3/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1
Backup battery - https://www.amazon.com/gp/product/B07YRZYLKV/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1

Everything mounted tidy in a project box. Ultrasonic tx/rx poking through the lid.
![IMG_6656](https://user-images.githubusercontent.com/6666082/197527056-63d4d01e-3469-43c3-92bd-9583d641fa4e.jpg)
Magnetic reed switch mounted to end of track to verify open state
![IMG_6657](https://user-images.githubusercontent.com/6666082/197527064-1663b249-679d-456b-886e-71c61924c5a7.jpg)
Magnetic reed switch mounted to top of door to verify closed state
![IMG_6658](https://user-images.githubusercontent.com/6666082/197527069-54a0d3f7-875f-4cbd-8f3d-d43318b62d37.jpg)
All sensors and controls exposed in Home Assistant
![Screenshot 2022-10-24 at 7 37 09 AM](https://user-images.githubusercontent.com/6666082/197527087-9a2ad8cb-a5d8-41c8-92b7-350b9caf5ec6.png)
