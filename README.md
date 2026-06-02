# breath-analyzer-diabetes

# Non-Invasive Breath Analyzer for Diabetes Monitoring

## Description
This project presents a portable, non-invasive diabetes screening system that uses breath acetone analysis instead of traditional blood-based methods.

The system integrates a multi-sensor array with an ESP32 microcontroller and an Android application to provide real-time, user-friendly health insights.

## Objective
To develop a painless, low-cost, and portable alternative for routine diabetes screening using breath-based analysis.

## Technologies Used
- ESP32 Microcontroller
- MQ-series Gas Sensors + WSP2110 Acetone Sensor
- ADS1115 ADC Modules
- Android Application (Bluetooth Communication)
- Embedded C / Firmware

## Key Features
- Non-invasive breath-based diabetes screening
- Straw-based sampling system for hygienic intake
- Multi-sensor array for acetone detection
- Real-time data acquisition and processing
- Bluetooth communication with mobile app
- Offline data storage and trend analysis

## System Workflow
1. User exhales into straw-based intake system
2. Sensors capture acetone and VOC variations
3. ESP32 processes real-time sensor data
4. Data transmitted via Bluetooth to Android app
5. App analyses and displays result:
   - Normal
   - Needs Attention
6. Data stored for future trend analysis

## Hardware Architecture
- Mixed sensor array (MQ sensors + WSP2110)
- Dual ADS1115 for high-resolution data acquisition
- ESP32 for control and communication
- Lithium battery + power regulation system

## Methodology
- 30-second testing cycle:
  - Baseline → Breath → Recovery
- Sample vs baseline comparison
- Sensor voting mechanism for classification
- Confidence score calculation

## Dataset
- 40 participants
  - 20 diabetic
  - 20 non-diabetic
- Real-time breath data collected and analyzed

## Results
- Reliable differentiation between diabetic and non-diabetic samples
- Fast testing (30–60 seconds)
- Low-cost operation (~₹0.5/day)
- Portable and suitable for field use

## Key Insights
- Breath acetone is a strong indicator of metabolic conditions
- Multi-sensor fusion improves reliability
- Non-invasive methods improve user compliance
- Environmental factors affect sensor readings

## Advantages
- Completely painless and non-invasive
- Extremely low recurring cost
- Portable and easy to use
- Suitable for large-scale screening

## Limitations
- Not a replacement for clinical diagnosis
- Sensitive to environmental conditions
- Requires calibration for consistency

## Future Work
- Integrate machine learning for improved accuracy
- Improve enclosure and airflow design
- Add BLE and cross-platform support
- Miniaturization using PCB design

## My Contribution
- [We will customize this based on your exact role]
