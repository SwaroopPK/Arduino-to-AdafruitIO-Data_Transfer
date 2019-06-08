# Arduino--Adafruit-Data-Transfer

This project deals with data logging of voltage values of an LED using a potentiometer. The components used are 

1. Node MCU ESP8266
2. LED
3. 10K Potentiometer

We have made use of Adafriut Cloud Service. For information about Adafruit, refer [https://www.adafruit.com/about](https://www.adafruit.com/about).

The circuit was setup as shown in the figure. 

The two fixed ends of the potentiometer was connected to 3V supply and GND(Ground). The variable end was connected to an analog pin of the MCU(A0 Pin). The ADC pin has a 10-bit resolution, which means you'll get values between 0 and 1024. These values were converted to voltage values. As the potentiometer knob was varied, the voltage values were sent over to the Cloud Service. These values were displayed on a graph as shown.