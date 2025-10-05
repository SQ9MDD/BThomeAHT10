# ESP32-C3 AHT10 BTHome Sensor

Firmware for an ultra-low-power **ESP32-C3** node broadcasting temperature, humidity, and battery data via **BTHome v2** BLE advertisements.

---

## 🇬🇧 English

### Features
- Measures **temperature** and **humidity** using the **AHT10** sensor  
- Reports **battery voltage** and **estimated charge level**  
- Operates in **deep sleep** mode for ultra-low power consumption  
- Fully compatible with **Home Assistant** (BTHome integration)  
- Designed for simple, wireless environmental monitoring  

### Hardware
- **ESP32-C3** (e.g. DevKitM-1)  
- **AHT10** (I²C, 0x38)  
- Voltage divider for VBAT monitoring  

### Configuration
- Deep sleep duration: `GPIO_DEEP_SLEEP_DURATION` (seconds)  
- BLE transmit power: `TX_DBM`  
- ADC calibration: `CAL_K`, `CAL_BmV`  
- I²C power control pin: `i2c_power`  

---

## 🇵🇱 Polski

### Funkcje
- Pomiar **temperatury** i **wilgotności** z czujnika **AHT10**  
- Raportowanie **napięcia baterii** i **szacowanego poziomu naładowania**  
- Tryb **głębokiego uśpienia** zapewniający minimalny pobór energii  
- Pełna kompatybilność z **Home Assistant** (integracja BTHome)  
- Prosty, bezprzewodowy czujnik środowiskowy  

### Sprzęt
- **ESP32-C3** (np. DevKitM-1)  
- **AHT10** (I²C, adres 0x38)  
- Dzielnik napięcia do pomiaru VBAT  

### Konfiguracja
- Czas uśpienia: `GPIO_DEEP_SLEEP_DURATION` (sekundy)  
- Moc nadawania BLE: `TX_DBM`  
- Kalibracja ADC: `CAL_K`, `CAL_BmV`  
- Zasilanie magistrali I²C: `i2c_power`  

---

## Author / Autor
(c) 2025 **Rysiek Labus** – [SQ9MDD](https://sq9mdd.qrz.pl)
