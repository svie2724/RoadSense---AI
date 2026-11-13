# 🚗 RoadSense AI
### AI-Powered Smart Road Condition Monitoring System

RoadSense AI is a smart road monitoring prototype designed to detect potholes and road surface irregularities using sensors, GPS, IoT connectivity, and cloud-based visualization.

The system collects road-impact data from vehicles and displays detected road conditions on a live dashboard to support better road safety and maintenance.

## 🎯 Project Objectives

- Detect potholes and road irregularities.
- Monitor road conditions using sensors.
- Identify geographical locations using GPS.
- Upload detection data to Firebase.
- Visualize road conditions through a live dashboard.
- Assign severity levels to detected road impacts.

## 🛠️ Technologies Used

| Component | Technology |
|---|---|
| Microcontroller | ESP32 |
| Accelerometer | MPU6050 |
| GPS Module | NEO-6M |
| Cloud Database | Firebase Realtime Database |
| Frontend | HTML, CSS, JavaScript |
| Map Visualization | Leaflet.js |
| Programming | Embedded C/C++, Python |
| Simulation | Python |

## ⚙️ System Architecture

1. **Data Collection:** MPU6050 collects acceleration data.
2. **Pothole Detection:** ESP32 calculates acceleration changes and identifies significant road impacts.
3. **GPS Tracking:** NEO-6M provides geographical coordinates.
4. **Cloud Communication:** Detection information is uploaded to Firebase.
5. **Dashboard:** A web dashboard displays road reports, severity levels, and locations.
6. **Confidence Scoring:** Multiple reports from the same location increase the confidence score.

## 📊 Key Features

- Real-time road-impact monitoring.
- GPS-based location tracking.
- Five-level severity classification.
- Firebase cloud integration.
- Interactive road monitoring dashboard.
- Simulated vehicle reports for demonstration.

## 📁 Project Structure

```text
RoadSense-AI/
│
├── firmware/
│   └── roadsense_firmware/
│
├── dashboard/
│   └── index.html
│
├── firebase/
│   ├── README.md
│   └── database.rules.json
│
├── tools/
│   ├── simulate_vehicles.py
│   └── requirements.txt
│
├── docs/
│   ├── ARCHITECTURE.md
│   ├── HARDWARE.md
│   ├── EXPERIMENTS.md
│   ├── TROUBLESHOOTING.md
│   └── FAQ.md
│
├── presentation/
│
├── LICENSE
└── README.md
```

## 🔮 Future Enhancements

- Machine learning-based pothole classification.
- Improved real-time road monitoring.
- Advanced road condition analysis.
- Better location-based clustering.
- Authenticated device communication.
- Large-scale road condition monitoring.

**Note:** The current prototype uses threshold-based detection rather than a trained AI model. Machine learning classification and real-road performance evaluation are planned future enhancements.

## 👩‍💻 Team VisionQuest

St. Joseph's College of Engineering, Chennai.

Project: RoadSense AI

## 📜 License

This project is licensed under the MIT License.
