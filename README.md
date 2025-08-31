# RFID-Based-Door-Lock-System
🚪🔑 A simple RFID-based access control system that uses RFID tags to grant or deny access. Designed for smart security applications like doors, labs, and restricted areas.

# ✨ Features

Reads RFID tags using an RFID reader module (e.g., RC522).

Authenticates users based on pre-registered IDs.

Grants or denies access with visual (LED) & audio (buzzer) alerts.

Can be extended to log data or control electronic locks.

# 🛠️ Components Used

RFID Reader (RC522 / EM-18)

RFID Tags / Cards

Arduino / ESP32 / Microcontroller

Buzzer

LEDs (Green/Red for status)

Power supply

# ⚙️ Working

When an RFID tag is scanned, its unique ID is read by the reader.

The microcontroller compares the ID with stored valid IDs.

If matched → Access is granted (Green LED ON, buzzer beep, door unlock).

If not matched → Access denied (Red LED ON, warning buzzer).


# 🚀 How to Run

Connect the RFID reader module to Arduino/ESP32 as per circuit diagram.

Upload the code from the code/ folder.

Power the system and scan RFID tags.

Modify the code to add/remove authorized IDs.

# 📸 Circuit Diagram
<img width="658" height="550" alt="Image" src="https://github.com/user-attachments/assets/d11401d1-8e22-4f9f-b55e-add256100464" />
