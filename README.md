# 🚗 ESP32 RC Webinterface

Ein einfaches Webinterface zur Steuerung eines RC-Fahrzeugs mit dem ESP32.  
Das System ermöglicht **Lenkung**, **Gangschaltung** und **Geschwindigkeitsregelung** – direkt über den Browser!

---

## 🔧 Funktionen

- 🕹️ **Lenkung** (z. B. via Slider oder Buttons)
- ⚙️ **Gangschaltung** (mehrere Fahrmodi / Gänge)
- ⚡ **Geschwindigkeitsregelung**

---

## 📶 WLAN-Verbindung

Der ESP32 erstellt ein eigenes WLAN-Netzwerk:

- **SSID:** `ESP-Steureung`  
- **Passwort:** `12345678`

Sobald du mit dem WLAN verbunden bist, rufe folgende Adresse im Browser auf:

- 🌐 **Webinterface:** [http://192.168.4.1](http://192.168.4.1)

---

## 🚀 Installation

1. **Code auf den ESP32 hochladen**  
   Der Code ist bereits einsatzbereit und muss nur noch auf dein ESP32-Modul übertragen werden (z. B. mit Arduino IDE oder PlatformIO).

2. **ESP32 starten**  
   Nach dem Start erstellt der ESP32 automatisch das WLAN.

3. **Mit dem WLAN verbinden**  
   SSID: `ESP-Steureung`  
   Passwort: `12345678`

4. **Browser öffnen**  
   Rufe [http://192.168.4.1](http://192.168.4.1) auf und steuere dein Fahrzeug!

---

## 📁 Dateien

> 🔹 Der gesamte Code ist im `src/`-Ordner enthalten.  
> 🔹 HTML, CSS und JS für das Webinterface sind integriert.

---

## 🛠️ Anforderungen

- ESP32 Dev Board (z. B. DOIT ESP32 DEVKIT V1)
- Arduino IDE oder PlatformIO
- Optional: Servos, Motorcontroller, RC-Hardware
