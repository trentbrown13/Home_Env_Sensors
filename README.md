# Home_Env_Sensors
This project started as my first forray into IOT - We inherited a very old "demo" hot tub with no way to monitor or control it. My wife wanted a way to monitor it's temperature, so I bought an Ardiuino starter kit and away we went.

Things have evolved since then, its now an ESP8255 contraption with 1 BME sensor and 0 - 2 dallas temp sensors depending on the location. The patio area has one inside BME sensor and two waterfroof DS18B20 snesors, one in the hot tub, the other up in the eaves. All readings are displayed on a 4 x 20 LCD display triggerd by a distance sendor to conserve battery power. These and many more readings are also trasmitted to a NodeRed server running on a RPI so I can now remotly monitor the environment readings, battery level (this is all solar) etc.
