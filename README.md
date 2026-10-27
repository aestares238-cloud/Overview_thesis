
# AirBnBrrr: AI-Powered HVAC IoT Monitoring System

AirBnBrrr is an ongoing academic project focused on monitoring the operating conditions of non-inverter window-type air conditioners. It collects real-time sensor data and processes it to identify abnormal operating conditions, generate diagnostic reports, and send automated SMS alerts.

## Key Features

- **IoT Telemetry Monitoring:** Collects temperature, humidity, vibration, voltage, power consumption, and dust-level readings from a sensor system.
- **Machine Learning Anomaly Detection:** Uses the Isolation Forest algorithm to identify unusual patterns in sensor readings.
- **Rule-Based Diagnostics:** Evaluates operating measurements against predefined engineering thresholds to identify potentially abnormal conditions.
- **AI-Assisted Analysis:** Uses a large language model (LLM) to generate contextual diagnostic reports based on monitoring data.
- **Automated SMS Alerts:** Sends notifications to designated contacts when configured alert conditions are triggered.
- **Web Dashboard:** Visualizes real-time telemetry, anomaly reports, and monitoring information through a web interface.

## Technology Stack

- **Backend:** Python, FastAPI
- **Database:** PostgreSQL, Supabase
- **Machine Learning:** scikit-learn, Isolation Forest
- **Frontend:** HTML, JavaScript, Tailwind CSS, Lucide Icons
- **Hardware:** Raspberry Pi 5, ESP32, sensor modules
- **Integrations:** Generative AI APIs, SMS Gateway

## System Architecture

1. The ESP32-based sensor system collects measurements from the air conditioning unit.
2. Sensor data is transmitted to the backend for processing and storage.
3. The anomaly detection model identifies unusual patterns in the collected measurements.
4. A rule-based diagnostic system evaluates measurements against predefined thresholds.
5. AI-assisted analysis generates additional diagnostic context when applicable.
6. The system records the results and sends notifications when configured alert conditions are met.

## Project Status

Ongoing academic project developed as part of the Bachelor of Engineering Technology program, majoring in Instrumentation and Control Technology.

---

*This repository provides a project overview only. Source code and internal implementation details are not included.*
