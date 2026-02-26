# 📟 APX Digital: Industrial Tactical Radio
**A rugged, high-performance SDR-style radio interface for Windows.**

APX Digital is a lightweight desktop application designed to stream public safety, aviation, and emergency service broadcasts. It features a custom-built industrial UI inspired by professional-grade handheld transceivers (LMR) and utilizes a low-latency audio engine.

---

## 🛠 Key Features

* **Industrial Beveled UI:** A high-contrast, tactical interface designed for visibility and ease of use.
* **Tactical Sound Effects:** * **Talk Permit Tone:** Authentic digital "chirp" handshake upon connection.
    * **Squelch Tail:** Realistic static pop when ending transmissions.
    * **Tactical Keypad:** High-frequency sine wave "clicks" for tactile feedback.
* **Real-Time Visualizer:** 5-band frequency analyzer responding to active voice streams on the LCD.
* **Portable Engine:** Powered by **NAudio**, meaning no external VLC or native DLL installations are required.

---

## 🚀 Installation & Usage

### 1. Download
Grab the latest standalone `.exe` from the Releases section.

### 2. Tuning
* Enter a 5-digit **Broadcastify Node ID** using the keypad.
* Example: `19119` (JFK International Airport Tower).
* Press **JOIN NETWORK** to authenticate.

### 3. Presets
**Right-click** the `JOIN NETWORK` button to access a quick-list of global emergency and aviation hubs.

---

## 🧰 Technical Specifications

| Feature | Specification |
| :--- | :--- |
| **Language** | C# 12 |
| **Framework** | .NET 8.0 (WPF) |
| **Audio Engine** | NAudio (MediaFoundationReader) |
| **Encoding** | MP3 / AAC Digital Stream |
| **UI Rendering** | Custom XAML ControlTemplates |

---
