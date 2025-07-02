# ❤️ Embedded Wavelet–Neural Network for ECG Analysis

This project presents a hybrid approach that combines **wavelet-based signal processing**, **artificial neural networks (ANNs)**, and **embedded IoT deployment** to analyze ECG signals in real time. The goal is to enable accurate heartbeat classification and anomaly detection using lightweight models that can run on microcontrollers like the **ESP8266**, with cloud integration for remote monitoring.

---

## 🧠 What is ECG Analysis?

**Electrocardiogram (ECG)** analysis involves interpreting the electrical activity of the heart to detect abnormalities such as arrhythmias, tachycardia, or atrial fibrillation. ECG signals are time-series waveforms that reflect the heart's rhythm and electrical conduction.

Key components of an ECG waveform:
- **P wave**: Atrial depolarization
- **QRS complex**: Ventricular depolarization
- **T wave**: Ventricular repolarization

Accurate ECG analysis is critical for early diagnosis of cardiovascular diseases. This project enhances traditional analysis by combining **wavelet transforms** (for denoising and feature extraction) with **neural networks** (for classification).

---
Architecture-
![image](https://github.com/user-attachments/assets/7b817075-f2ff-4541-8bbd-ee084cf00002)

## 🚀 Project Highlights

- ✅ **Wavelet-based preprocessing** to denoise and extract features from raw ECG signals
- ✅ **ANN and CNN models** trained for heartbeat classification
- ✅ **Deployment-ready code** for ESP8266 using MicroPython
- ✅ **Real-time signal acquisition and cloud integration**
- ✅ **Visualization notebooks** for signal processing and model evaluation

---

## To get started 
1. install the dependencies-
- numpy
- scipy
- matplotlib
- tensorflow (prefered) or keras
- pywavelets

2. Install with 
pip install -r requirements.txt

3. Run preprocessing
Use the wavelet preprocessing notebook to denoise ECG signals and extract features.

5. Train the model
Use the ANN or CNN notebooks to train a classifier on the processed ECG data.

7. Deploy to ESP8266
Use the MicroPython deployment notebook to flash the model and run real-time inference on embedded hardware.


Anatomy of the heart-
![image](https://github.com/user-attachments/assets/608984f4-e7da-4abd-874f-459245b9c715)

Wavelet Decomposition-
![image](https://github.com/user-attachments/assets/04997da3-20bb-4484-826a-f3e267bdf827)

ECG Segments-
![image](https://github.com/user-attachments/assets/328bd038-70b3-470b-8722-edb0daa1ee43)

CNN Architecture-
![image](https://github.com/user-attachments/assets/4cf373ee-210a-4549-bddf-160a517c9dd9)

# 📊 Results
- Achieved high classification accuracy on benchmark ECG datasets
- Demonstrated real-time inference on ESP8266 with minimal latency
- Successfully integrated cloud-based logging for remote monitoring

![image](https://github.com/user-attachments/assets/32fa5ab2-3527-44bd-9cd7-cf247caa8e6f)

📎 References
- MIT-BIH Arrhythmia Dataset
- Wavelet Transform for ECG Denoising
- MicroPython on ESP8266

