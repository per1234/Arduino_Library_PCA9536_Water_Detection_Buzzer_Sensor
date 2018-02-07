[![PCA9536_WDBZ](PCA9536_WDBZ_I2CBZ.png)](https://store.ncd.io/product/water-detection-sensor-with-buzzer/)

# PCA9536_WDBZ

This Water Sensor is designed to detect water or liquid leakage.  Convenient I2C interface makes it easy to add water leakage detection to any IoT application in seconds.  Integrated on-board Buzzer can be used for alarm notification applications. This Water detect Sensor uses a PCA9536 digital IO to detect the water and to control the buzzer.
This Device is available from www.ncd.io 

[SKU: PCA9536_WDBZ_I2CS]

(https://store.ncd.io/product/water-detection-sensor-with-buzzer/)
This Sample code can be used with Arduino.

Hardware needed to interface PCA9536_WDBZ sensor with Arduino

1. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-nano/">Arduino Nano</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-micro-with-i2c-expansion-port/">Arduino Micro</a>

3. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-uno/">Arduino uno</a>

4. <a href="https://store.ncd.io/product/dual-i2c-shield-for-arduino-due-with-modular-communications-interface/">Arduino Due</a>

5. <a href="https://store.ncd.io/product/water-detection-sensor-with-buzzer/">PCA9536_WDBZ Water detection Sensor With Buzzer</a>

6. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

PCA9536_WDBZ:

This Water Sensor is designed to detect water or liquid leakage.  Convenient I2C interface makes it easy to add water leakage detection to any IoT application in seconds.  Integrated on-board Buzzer can be used for alarm notification applications. This Water detect Sensor uses a PCA9536 digital IO to detect the water and to control the buzzer.

Applications:

• Water leakage detection applications.

How to Use the PCA9536_WDBZ Arduino Library

The PCA9536_WDBZ has a number of settings, which can be configured based on user requirements.
          
1.Address calling:The following command is used to call the PCA9536_WDBZ sensor to begin the transmission.

            pca.getAddr_PCA9536_WDBZ(PCA9536_WDBZ_DEFAULT_ADDRESS);           // 0x41
            
 2.Reset:The following command is used to reset the module.
 
            pca.Reset();
            
3.Sensor setup:The following command is used to setup the sensor.

           pca.setPinMode(PCA9536_WDBZ_OUTPUT_PIN0, PCA9536_WDBZ_MODE_OUTPUT);

