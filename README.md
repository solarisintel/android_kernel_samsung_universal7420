## Galaxy S5 Docomo (SC-05G) android 10 kernel

### not working 
1) mdm_helper(kickstart)
/dev/efs_hsic_bridge is not generated
/dev/ttyUSB0         is not generated

### working
1) sensor
2) wifi
3) camera
4) adb, mtp
5) touch panel
6) button

sensor (sensors.universal7420.so)
Accelerometer MPU6500   working
Gyroscope     MPU6500   working
Magnetic      AK09911C  working
Light         TMD4903   not working
Barometer     BMP280    not working 
compass       AK09911   not working

