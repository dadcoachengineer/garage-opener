Garage door project to convert my Liftmaster MyQ opener to local only operation. They have had a few outages over the past year and I also think it is quite silly to send some things to/from cloud services.

[ESPHome YAML Config](https://github.com/dadcoachengineer/garage-opener/blob/main/config.yaml)

**Component list:**

[ESP32](https://www.amazon.com/gp/product/B07BK435ZW/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) - I have had really good luck with this brand of ESP microcontrollers.

[Relay](https://www.amazon.com/gp/product/B0798CZDR9/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) - I prefer using 3V relays so you don't have to level shift.

[Ultrasonic Sensor](https://www.amazon.com/gp/product/B01JG09DCK/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) - Surprisingly accurate given the pricepoint.

[Project box](https://www.amazon.com/gp/product/B08PP1W8Q3/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) - These boxes are not cheap but really well built, come with water tight glands and gasketed lid.

[Backup battery](https://www.amazon.com/gp/product/B07YRZYLKV/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) - I bought this for another project and it is totally overkill for this but....oh well.

[Close sensor](https://www.amazon.com/gp/product/B005H3GCW0/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1) - Our garage door is a little unique in how it closes so this sensor was perfect.

[Open sensor](https://www.amazon.com/gp/product/B01GJ82QE4/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1) - An open sensor is probably superflous but it is nice to have positive confirmation that the door is fully open.


<img width="961" alt="Screenshot 2022-10-24 at 5 00 07 PM" src="https://user-images.githubusercontent.com/6666082/197638230-5ef13859-d186-4397-b882-2edd0b7aaf78.png">

All sensors and controls exposed in Home Assistant
![Screenshot 2022-10-24 at 7 37 09 AM](https://user-images.githubusercontent.com/6666082/197527087-9a2ad8cb-a5d8-41c8-92b7-350b9caf5ec6.png)
