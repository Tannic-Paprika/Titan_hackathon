# Titan_hackathon
## Launching
### In order to run the website
```bash
python login.py
```
Then click on the link provided in the terminal
```bash
http://127.0.0.1:5000
```
This will launch the website. In order to check your fitness, first login with your username and password and then click on Check your fitness button. This will take you to a page which will show you the live sensor data along with your stress level and fitness index prediction and you can also see your BMI index

Or you an directly visit this link where we have hosted our website
```bash
https://titan_hackathon.pythonanywhere.com/
```

This project aims at developing an innovative solution that uses non-invasive methods or facial reading technologies to collect health vitals and derive a fitness score that is accurate, reliable, scalable, and can be deployed in various settings, from individual homes to large healthcare organizations.The model has an accuracy of 94%.

Our solution approach is:

- Collection of health data from multiple sensors like heart rate sensor[MAX30100](https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwiBwtSgl5OAAxVokmYCHayHARYYABADGgJzbQ&ae=2&ohost=www.google.com&cid=CAESbeD24wXBk5ZzJFf2u8SABNRn9sXr6rfA9lxRIw6pJDPRrm0YF-2hxxY0dIUxZqDdhSeYgL-WT3kGR5HcEi2M3wqlTsLS1hauIALa5dBEvMEIMQLdFRuNWlTGGSYd0jCW9pT9S3PNhVb0ESJ-XLM&sig=AOD64_0GYnq2_s3afIoi7u4te_2mJRxxEA&ctype=5&q=&ved=2ahUKEwi068qgl5OAAxU1amwGHRNZDyUQ9aACKAB6BAgGEBU&adurl=), accelerometer[(MPU6050)](https://robu.in/product/mpu-6050-gyro-sensor-2-accelerometer/), [ESP-32 CAM Wifi Module](https://www.electronicscomp.com/esp32-cam-wifi-module-bluetooth-with-ov2640-camera-module-2mp-for-face-recognization?gclid=Cj0KCQjwqs6lBhCxARIsAG8YcDjopqELU-LpxUKawFz5oCwQjMG2bDbsRsNPxCS4mywbILHjh4zcjdAaAliMEALw_wcB), [blood glucose sensor](https://www.researchgate.net/figure/Working-principle-of-the-glucose-sensor-patch-and-characterization-in-a-semi-infinite_fig1_358801890) and [temperature sensor](https://eepower.com/resistor-guide/resistor-types/ntc-thermistor/)
- Storing data on Firebase database

- Data analyis and training using several ML Algorithms
- Model Deployment 

