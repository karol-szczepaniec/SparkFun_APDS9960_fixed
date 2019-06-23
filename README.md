This folder should contain the .cpp and .h files for the library. 

If backward compatibility is needed, source code should be placed in the library root folder and in a "utilyt" folder. 

Check out the [library specification](https://github.com/arduino/Arduino/wiki/Arduino-IDE-1.5:-Library-specification) for more details. 

Some of ADPS 9600 don't work with standard asets.
Changing:

/* APDS-9960 I2C address */
#define APDS9960_I2C_ADDR       0x39 // make sure your device I2C adress is 0x39

/* Acceptable device IDs */
#define APDS9960_ID_1           0xA8 // 0xAB - default. 
