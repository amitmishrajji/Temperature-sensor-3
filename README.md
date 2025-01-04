# Temperature-sensor-3
**Name: AMIT MISHRA** 
**Company: CODTECH IT SOLUTIONS**
**ID: CTO8DAQ**
**Domain: EMBEDDED SYSTEMS**
**Duration: 12TH DECEMBER 2024 TO 12TH JANUARY 2025**
**Mentor: N.SANTHOSH**

This Tinkercad project demonstrates how to measure temperature using an LM35 temperature sensor, a potentiometer, a 16x2 LCD, and an Arduino. The project uses the LM35 sensor to detect temperature, the potentiometer to adjust the LCD brightness, and the Arduino to process and display the temperature readings on the LCD. The 16x2 LCD is employed to show the real-time temperature, making the project ideal for applications requiring temperature monitoring, such as weather stations, home automation systems, or basic educational experiments.

The LM35 is a widely used temperature sensor that provides an analog output proportional to the surrounding temperature. It outputs 10 mV per degree Celsius, making it simple to integrate with Arduino. The potentiometer is used as a contrast control for the LCD, ensuring clear visibility of the displayed characters under various lighting conditions. The Arduino processes the data from the LM35 and converts the analog signal into a readable temperature value, displayed on the LCD in degrees Celsius.

To set up the hardware, connect the LM35 temperature sensor to the Arduino. The sensor has three pins: VCC, GND, and output. Connect VCC to the 5V pin on the Arduino, GND to the ground pin, and the output to one of the Arduino's analog input pins, such as A0. The potentiometer is connected to the LCD's V0 pin, which controls the contrast. One side of the potentiometer is connected to the Arduino's 5V pin, the other to GND, and the middle pin to the LCD's V0 pin. The LCD is connected to the Arduino using the appropriate pins for RS, EN, D4, D5, D6, and D7, as specified in the code.

The Arduino code initializes the LCD and sets up the pins for the temperature sensor and the potentiometer. It then continuously reads the analog signal from the LM35 sensor, converts it into a voltage, and calculates the temperature using the LM35's characteristic of 10 mV per degree Celsius. The calculated temperature is displayed on the LCD, and it is also sent to the Serial Monitor for debugging or logging purposes. The LCD is updated every second to reflect the latest temperature reading.

The potentiometer plays a crucial role in adjusting the visibility of the characters displayed on the LCD. By turning the potentiometer, the contrast of the LCD can be adjusted to ensure the text is clearly visible. This feature is particularly useful in varying lighting conditions or when the LCD is viewed from different angles.

This project offers a practical demonstration of interfacing sensors with Arduino and is a simple yet effective way to measure temperature. It teaches key concepts such as reading analog inputs, processing sensor data, and controlling an LCD. The project can be extended further by integrating additional sensors or modules, such as a humidity sensor or a Wi-Fi module, to create a more comprehensive environmental monitoring system. It can also be modified to include alarms or notifications when the temperature crosses certain thresholds.

In summary, this Tinkercad project is an excellent example of how Arduino can be used in basic electronic applications. It effectively combines a temperature sensor, potentiometer, LCD, and Arduino to create a functional and educational temperature monitoring system. The project is easy to build and requires minimal components, making it ideal for beginners or those looking to learn the basics of Arduino and sensor integration. It also provides a foundation for more advanced projects involving sensors and data visualization.
