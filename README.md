# Smart Shoes for Blind and Deaf
# Smart Shoes for the Blind and Deaf  

A cost-effective, innovative solution designed to assist visually and hearing-impaired individuals in navigating their surroundings and ensuring their safety through real-time obstacle detection, haptic feedback, and GPS-based location tracking.  

---

## Features  
- **Obstacle Detection:** Utilizes ultrasonic sensors to detect objects in the user's path and alert them.  
- **Haptic and Audio Feedback:** Provides directional guidance through vibration motors and optional buzzers.  
- **Real-Time Location Tracking:** Sends GPS coordinates to emergency contacts via GSM module in critical situations.  
- **Lightweight and User-Friendly:** Designed for daily use with an emphasis on comfort and affordability.  
- **Customizable and Scalable:** Can be adapted to various footwear types and upgraded with additional features.  

---

## Hardware Components  
| **Component**        | **Purpose**                                           | **Quantity** |  
|-----------------------|-------------------------------------------------------|--------------|  
| Arduino Nano          | Microcontroller for handling sensor inputs and outputs | 1            |  
| HC-SR04 Ultrasonic Sensor | Detects obstacles and measures distance            | 2            |  
| NEO-6M GPS Module     | Tracks real-time location                             | 1            |  
| GSM SIM900 Module     | Sends location updates via SMS                        | 1            |  
| Vibration Motors      | Provides tactile feedback to the user                 | 2-4          |  
| Buzzer                | Offers optional audio alerts                          | 1            |  
| Battery Pack          | Powers the system                                     | 1            |  
| Wires and Connectors  | Establish connections between components              | As needed    |  

---

## How It Works  
1. **Obstacle Detection:**  
   Ultrasonic sensors continuously scan the path and measure distances. If an obstacle is detected within the threshold range, the system activates.  

2. **Feedback Mechanism:**  
   - Vibrations: The motors provide directional haptic cues to the user.  
   - Audio Alerts: Buzzers emit sound (optional for hearing users).  

3. **Emergency Alert System:**  
   The GPS module retrieves the user's location, and the GSM module sends the coordinates to pre-configured emergency contacts.  

---

## Software Setup  
### Prerequisites  
- Arduino IDE  
- Required libraries:  
  - `TinyGPS++`  
  - `SoftwareSerial`  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/smart-shoes-blind-deaf.git
