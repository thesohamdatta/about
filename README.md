# Humane AI Pin - Hardware & Software Specifications
![image](https://github.com/user-attachments/assets/0de74a51-7001-46b7-bf76-96cc3bdf1acd)
As we know, **the Humane AI Pin is essentially a unique Android device** paired with a laser projection system. While Humane Inc. has discontinued its services (as of February 28, 2025, after being acquired by HP for $116M), the AI Pin's hardware remains functional and capable. Below are the detailed hardware and software specifications of the device.

## **Hardware Specifications**

### **Processor**
The Humane AI Pin is powered by the **Qualcomm Atoll AB** processor, which refers to the **Qualcomm Snapdragon 720G** chipset. The **"Atoll"** is the internal codename for the **Snapdragon 720G**, and the **"AB"** variant is a specific revision of this SoC.

- **CPU:**  
  - **Qualcomm Snapdragon 720G (_SM7125)_**
  - 2x Cortex-A76 @ **2.3 GHz** (Prime & Performance Cores)  
  - 6x Cortex-A55 @ **1.8 GHz** (Efficiency Cores)
  - **Officially listed as:** Octa-core @ **2.1 GHz** (Humane's spec page lists accelerated on-device AI performance)
- **GPU:** Adreno 618  
- **Process Node:** 8nm  
- **Modem:** Snapdragon X15 LTE  
- **Memory:** LPDDR4X support  
- **ISP:** Spectra 350L  
- **AI Engine:** 5th Gen Qualcomm AI Engine  

### **Memory & Storage**
- **RAM:** 4GB LPDDR4X  
- **Storage:** 32GB eMMC  

### **Physical Dimensions & Weight**
- **Ai Pin (main unit):**
  - **Weight:** 34.2 g
  - **Dimensions:** 44.50 mm × 47.50 mm × 14.98 mm (main body), projector module: 19.33 mm × 9.42 mm
  - **Depth (thinnest point):** 8.25 mm
- **Battery Booster:**
  - **Weight:** 20.5 g
  - **Dimensions:** 45.20 mm × 47.16 mm × 8.25 mm
- **Body:** Aluminum frame with Corning Gorilla Glass Victus touchpad (polished with optical coatings)
- **Colors:** Eclipse (Super Matte Black Anodized), Equinox (Polished Silver / Black Touchpad), Lunar (Polished Silver / White Touchpad)

### **Battery**
- **Type:** Built-in rechargeable lithium-ion polymer battery  
- **Charging:** Wireless power charging (proprietary Humane charging pad); also charges via the included charging case  
- **Battery Life:** ~4–5 hours of active use (device only); extended with Battery Booster hot-swap system (perpetual power system)  
- **Charging Case:** Provides an additional full charge for both the Pin and Battery Booster; accepts USB-C

### **Cellular Connectivity**
- **Dual Antenna MIMO**  
- **FDD‑LTE Bands:** 1, 2, 3, 4, 5, 7, 8, 12, 17, 20, 26, 66, 71  
- **TDD‑LTE Bands:** 38, 41  
- **UMTS/HSPA+/DC-HSDPA Bands:** 850, 900, 1700/2100, 1900, 2100 MHz  
- **Voice Support:** VoLTE, 3G  
- **SIM:** eSIM (Locked to Humane software but can be reprogrammed)
- **Network:** T-Mobile MVNO (US only, via Humane's own MVNO service — now discontinued)

### **Wi-Fi & Bluetooth**
- **Wi-Fi:** Wi-Fi 5 (802.11ac) with 2.4GHz + 5GHz  
- **Bluetooth:** Bluetooth 5.1  
  - **Supported Codecs:** SBC, AAC, LDAC, aptX™ HD  
  - **Supports common Bluetooth headsets and speakers**  

### **Location Services**
- **Satellite Navigation:** GPS, GLONASS, Galileo, BeiDou  
- **Additional:** Wi-Fi Positioning System, Assisted GPS  

### **Camera**
- **Resolution:** 13MP (4160 × 3120 px)
- **Video:** 1080p @ 30fps
- **Type:** Ultra Wide Camera
- **FOV:** 120°
- **Aperture:** f/2.4
- **Lens:** 5-element lens with single glass element
- **Focal Distance:** 40 cm ~ Infinite

### **Sensors**
- **Light Sensor:** Ambient light sensor  
- **Motion Sensors:** Accelerometer and gyroscope  
- **Position Sensor:** Magnetometer + GPS  
- **3D Depth Sensor:** Indirect Time-of-Flight (iToF) Camera  
  - **FOV:** 125°  
  - **Aperture:** f/1.4  
  - **Lens:** 4-element lens  
  - **Resolution:** 640×480 px (VGA)  

### **Audio**
- **Microphone:** Dual microphone array (AI Mic)
- **Speaker:** Built-in Personic Speaker (uses Head Related Transfer Function / HRTF for a personalized sound bubble)
- **Audio Codec (Speaker):** AAC
- **Bluetooth Audio Codecs:** SBC, AAC, LDAC, aptX™ HD
- **Voice Calling:** VoLTE, 3G

### **Laser Projection System aka Display**
- **Resolution:** 720p  
- **Technology:** Laser Beam Scanning (LBS) projection system — MEMS-based micro-electromechanical laser projector  
- **Laser Source:** Custom-Color Single-Diode Laser  
- **Laser Safety Classification:** Class 2 per IEC 60825-1:2014  
- **Operating Distance:** 20 cm to 40 cm  
- **Projection Angle:**  
  - **Horizontal:** 18.2° wide  
  - **Vertical:** 13.3° tall  
  - **Diagonal:** 22.4°  
- **Projection Size:** 7 cm × 9.6 cm at 30 cm distance  
- **Color:** Green monochrome  

### **Indicators**
- **Trust Light:** Light bar with 3 RGB LEDs — signals Capture, Phone, Mic, Scan, and Powering On states
- **Beacon:** Single RGB LED — provides silent pulse alerts for calls, messages, thermal warnings, and booster status

### **Input / Interaction**
- **Touchpad:** Corning Gorilla Glass Victus (polished with optical coatings), capacitive
- **One-Finger Gestures:** Tap & Hold (voice input), Double Tap (answer/end call, start/stop music), Swipe Left/Right (previous/next track), Drag Up/Down (volume)
- **Two-Finger Gestures:** Tap & Hold (translation), Double Tap (photo), Double Tap & Hold (video)
- **Voice:** Primary interaction method via dual mic array
- **Projection Gestures:** Tilt and pinch hand movements to navigate projected UI

### **Magnet / Wearability**
- **System:** Custom-designed magnetic array that self-aligns for wearability through apparel
- **Compatible fabrics:** Ultrathin, Thin, Normal, Thick, Thicker
- **Accessories:** Latch (lightweight fabrics), Clip (thicker apparel, straps, bags)

### **Environmental Specifications**
- **Operating Temperature:** 5°C to 35°C (41°F to 95°F)
- **Operating Altitude:** Up to 10,000 feet (3,000 meters); suitable for use in pressurized aircraft cabins

## **Software Specifications**

### **Operating System**
- **CosmOS** — Humane's custom AI-first operating system, built on Android  
  - Android 12 (System/Product)  
  - Android 11 (Vendor)  
- **Kernel:** Linux 4.14 (Version: 4.14.190) (based on Qualcomm tag)

### **CosmOS Architecture**
- **Ai Bus:** Core AI orchestration framework — routes requests to appropriate AI agents and services without requiring traditional app management
- **Agents:** Specialized AI programs for weather, news, music, vision, communication, task planning, etc.
- **LLM Integration:** Cloud-connected; powered via partnerships with Microsoft, OpenAI (ChatGPT / GPT-4), and others
- **Multimodal Input:** Voice, touch, text, gesture, and vision — combinable mid-interaction
- **Management Portal:** Humane.center (web app for managing photos, videos, notes, and device settings — now offline as of Feb 28, 2025)

### **Privacy & Security**
- **Trust Light:** Hardware indicator that activates whenever any sensor (camera, mic, etc.) is in use
- **Privacy Chip:** Dedicated on-device privacy chip for sensitive data
- **Secure Enclave:** Hardware-level security module
- **Activation:** Device requires manual touchpad interaction to begin listening — not always-on

### **Current Status**
- Humane discontinued services on **February 28, 2025**
- **HP acquired** Humane's CosmOS, IP (300+ patents), and team for **$116 million** in February 2025
- The AI Pin's cloud-dependent features (AI, calls, data) are no longer functional without modification
- All consumer data on Humane's servers was deleted upon shutdown

---

The AI Pin was designed to work with cloud-based AI services, but since it's just another Android device, we can modify it to run software like [CipherOS](https://github.com/CipherOS) or LineageOS on it. This document serves as a reference for developers and enthusiasts interested in reviving the Humane AI Pin.
