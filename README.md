ECG Box (ESP32-S3)

Real-time single-lead electrocardiography (ECG) monitoring system prototype built on ESP32-S3 for the Biomedical Sensor and Instrumentation final project (Computer Engineering, Universitas Brawijaya).

Key Features
- Real-Time ECG Acquisition: Single-lead signal reading using an AD8232 sensor module on ESP32-S3.
- Signal Processing: QRS complex detection using the Pan-Tompkins algorithm and heart rate (BPM) calculation.
- On-Device Visualization: Real-time waveform and heart rate display on an ST7796S TFT LCD screen.

Hardware & Stack
- Controller: ESP32-S3
- Sensor: AD8232 ECG Sensor
- Display: ST7796S TFT LCD
- Algorithm: Pan-Tompkins QRS detection
- Firmware: Arduino / C++ (ecg_box.ino)

Repository Structure
- ecg_box.ino - Main firmware handling sensor signal acquisition, Pan-Tompkins processing, and TFT display output.
