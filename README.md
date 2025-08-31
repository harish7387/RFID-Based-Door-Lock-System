# RFID + Keypad Based Security System

🔒 A dual authentication access control system using RFID tags and a keypad.
Both RFID card and password entry are required for secure access. Ideal for labs, lockers, offices, and restricted zones.

# ✨ Features

RFID-based user identification.

Keypad for password entry (extra security).

Dual authentication (RFID + PIN).

Visual indicators with LEDs and buzzer alerts.

Extendable for door locks, relays, or logging.

# 🛠️ Components Used

RFID Reader (RC522 / EM-18)

RFID Tags / Cards

4x4 Matrix Keypad

Arduino / ESP32 / Microcontroller

Buzzer

LEDs (Green/Red)

Relay Module (optional, for door lock)

Power supply

# ⚙️ Working

User scans RFID card.

If RFID tag is valid → system asks for PIN via keypad.

If both RFID & PIN match → Access Granted ✅ (Green LED, buzzer, door unlock).

If invalid RFID or wrong PIN → Access Denied ❌ (Red LED, buzzer alert).


# 🚀 How to Run

Connect RFID reader & keypad to Arduino/ESP32.

Upload code from code/ folder.

Register authorized RFID IDs & set PIN in code.

Power the system → Scan RFID + enter PIN → access granted.

# 📸 Output
<img width="658" height="550" alt="Image" src="https://github.com/user-attachments/assets/d11401d1-8e22-4f9f-b55e-add256100464" />
