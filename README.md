# 🚶 Fall Detection System for Senior Citizens

A smart wearable-based system designed to detect fall incidents in real-time and alert caregivers, improving the safety of elderly individuals.

---

## 🎯 Objective

* Enable reliable real-time fall detection using sensor data
* Reduce false alerts through intelligent analysis
* Improve safety and emergency response for senior citizens

---

## 🛠️ Hardware & Tools Used

* Arduino UNO
* ADXL345 Accelerometer

### 📚 Libraries

* Wire.h
* Adafruit_Sensor.h
* Adafruit_ADXL345_U.h

---

## ⚙️ Features

* Detects sudden motion changes using acceleration magnitude (AM)
* Confirms falls using angle variation analysis
* Designed for low-cost and portable implementation
* Real-time monitoring through Serial output

---

## 📊 Working Principle

The system continuously monitors acceleration values from the ADXL345 sensor.
A fall is detected based on:

1. Sudden spike in acceleration
2. Significant change in orientation

If both conditions are met, the system confirms a fall event.

---

## 📸 Sample Output

The system displays acceleration values and fall detection status through the Serial Monitor.

---

## 📌 Project Status

✅ Completed Mini Project
📄 Report Available

---

## 👩‍💻 Author

Dhevananda TV
