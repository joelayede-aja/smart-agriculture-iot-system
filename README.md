# Smart Agriculture IoT System

## Overview

The Smart Agriculture IoT System is an IoT-based environmental and soil monitoring solution designed for precision agriculture applications in resource-constrained environments.

The project integrates embedded systems, multiparameter soil sensing technologies, real-time monitoring, and Grafana-based data visualization to support efficient agricultural resource monitoring and sustainable farming practices.

The system is capable of monitoring key soil and environmental parameters including NPK values, soil moisture, temperature, electrical conductivity, and pH levels in real time.

This project was developed as part of a research-oriented initiative focusing on smart agriculture technologies adapted to developing countries such as the Democratic Republic of the Congo.

---

## Objectives

- Monitor soil and environmental parameters in real time
- Collect and analyze environmental data
- Support precision agriculture practices
- Enable real-time environmental visualization
- Develop low-cost smart agriculture solutions
- Promote sustainable technological innovation

---

## Features

- Real-time environmental monitoring
- Multi-parameter soil analysis
- NPK monitoring
- Soil moisture monitoring
- Soil temperature monitoring
- Electrical conductivity (EC) analysis
- Soil pH monitoring
- Grafana-based real-time visualization dashboard
- Embedded systems integration
- Serial communication between devices
- Modular and scalable architecture

---

## Environmental Parameters Monitored

The system is capable of monitoring multiple environmental and soil parameters in real time, including:

- Soil Nitrogen (N)
- Soil Phosphorus (P)
- Soil Potassium (K)
- Soil Moisture
- Soil Temperature
- Soil Electrical Conductivity (EC)
- Soil pH

## Technologies Used

### Programming Languages
- Python
- C++
- JavaScript
- HTML/CSS

### Embedded Systems & IoT
- Raspberry Pi model B
- ESP8266
- Arduino UNO
- Serial Communication
- Sensor Integration

### Monitoring & Visualization
- Grafana
- Real-time Dashboards

### Web Technologies
- Flask
- Bootstrap

---

## Hardware Components

- Raspberry Pi
- ESP8266 Wi-Fi Module
- Arduino UNO
- Multiparameter Soil Sensor
- DHT22 Temperature and Humidity Sensor
- Water Level Sensor
- LCD Display
- Relay Module
- Power Supply System

---

## System Architecture

The system architecture is based on real-time environmental data acquisition, embedded processing, and data visualization.

### Workflow

1. Environmental sensors collect real-time data
2. Sensor data is transmitted to the Raspberry Pi
3. Python applications process the collected data
4. Data is monitored and analyzed
5. Grafana dashboards visualize environmental parameters in real time
6. Users can monitor agricultural conditions through visualization interfaces

---

## Project Structure

```text
smart-agriculture-iot-system/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── docs/
├── images/
├── diagrams/
├── hardware/
├── software/
├── grafana/
├── web-dashboard/
└── data/
```
---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/joelayede-aja/smart-agriculture-iot-system.git
```

---

### 2. Navigate to the Project Directory

```bash
cd smart-agriculture-iot-system
```

---

### 3. Create a Python Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
```

Activate the virtual environment:

#### Linux / macOS

```bash
source venv/bin/activate
```

#### Windows

```bash
venv\Scripts\activate
```

---

### 4. Install Required Dependencies

```bash
pip install -r requirements.txt
```

---

### 5. Connect the Hardware Components

Connect:
- Raspberry Pi
- Multiparameter soil sensor
- ESP8266 module
- Water level sensor
- LCD display
- Environmental monitoring sensors

according to the project wiring configuration.

---

### 6. Configure Serial Communication

Verify the serial communication port used by the sensors.

Example:

```python
port = "/dev/ttyUSB0"
baudrate = 9600
```

---

### 7. Run the Application

```bash
python app.py
```

---

### 8. Access the Monitoring Dashboard

Open your browser and navigate to:

```text
http://127.0.0.1:5000
```

---

### 9. Launch Grafana Dashboard

Start Grafana service:

```bash
sudo systemctl start grafana-server
```

Access Grafana dashboard:

```text
http://localhost:3000
```

---

## Default Grafana Credentials

```text
Username: admin
Password: admin
```

You will be prompted to change the password after the first login.

---

## Research Contribution

This project contributes to research in:

- Smart Agriculture
- Precision Agriculture
- Internet of Things (IoT)
- Embedded Systems
- Environmental Monitoring
- Precision Soil Analysis
- Sustainable Agricultural Technologies

The project specifically focuses on low-cost and scalable environmental monitoring solutions adapted to resource-constrained environments.

---

## Future Improvements

- Automated irrigation system
- AI-based environmental prediction
- Edge computing integration
- Cloud synchronization
- Mobile application support
- Solar-powered optimization
- Machine learning for environmental analysis

---

## Author

### Joël Ayede Arindu

Computer Science Graduate  
Embedded Systems and IoT Research Enthusiast

### Research Interests
- Smart Agriculture
- Embedded Systems
- Internet of Things (IoT)
- Environmental Monitoring
- Artificial Intelligence

### Contact
- GitHub: https://github.com/joelayede-aja
- LinkedIn: https://linkedin.com/in/joel-ayede

---

## License

This project is intended for academic, educational, and research purposes.
