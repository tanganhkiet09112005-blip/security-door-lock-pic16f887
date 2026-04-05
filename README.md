# Security Door Lock System (PIC16F887)

Engineering project on building a security door lock system using a password with the PIC16F887 microcontroller, carried out by Team NTC (Kiệt & Mạnh) - IUH.

## System Structure (Hardware)
* **MCU:** PIC16F887 (Central processing unit).
* **Input:** 4x3 Keypad (Password input).
* **Output:** 16x2 LCD (Status display), Relay (Door latch control), Buzzer & LED (Alarm).
* **Storage:** Built-in EEPROM (Permanent password storage).

##  Key Features
* **Password management:** Allows users to change the password directly from the keypad.
* **EEPROM security:** Uses Marker writing technique (0xA5) to check the password setup status in memory.
* **Intrusion prevention mechanism:** The system automatically locks and triggers an alarm after 3 consecutive incorrect entries.
* **Master Reset:** Integrates an emergency code (9999) to restore the system to factory settings.

##  Project Structure

<img width="989" height="699" alt="image" src="https://github.com/user-attachments/assets/fc177fa1-3a03-416a-a773-899706432599" />

<img width="915" height="687" alt="image" src="https://github.com/user-attachments/assets/b1274b5b-f711-49ec-b4d6-a516fb6eaab8" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f193de51-a14b-4758-b727-a362b34feb94" />

