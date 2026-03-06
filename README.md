# Humane AI Pin - Hardware & Software Specifications
![image](https://github.com/user-attachments/assets/0de74a51-7001-46b7-bf76-96cc3bdf1acd)
As we know, **the Humane AI Pin is essentially a unique Android device** paired with a laser projection system. While Humane Inc. discontinued its services on **February 28, 2025** — following HP's acquisition of the company's software, IP, and team for **$116 million** — the AI Pin's hardware remains fully functional and capable. Below are the detailed hardware and software specifications of the device.

## **Hardware Specifications**

### **Processor**
The Humane AI Pin is powered by the **Qualcomm Atoll AB** processor, which refers to the **Qualcomm Snapdragon 720G** chipset. The **"Atoll"** is the internal codename for the **Snapdragon 720G**, and the **"AB"** variant is a specific revision of this SoC. Humane officially lists it as an octa-core processor running at **2.1 GHz**, which reflects the accelerated on-device AI configuration rather than the raw core speeds.

- **CPU:**  
  - **Qualcomm Snapdragon 720G (_SM7125_)**  
  - 2x Cortex-A76 @ **2.3 GHz** (Prime & Performance Cores)  
  - 6x Cortex-A55 @ **1.8 GHz** (Efficiency Cores)  
- **GPU:** Adreno 618  
- **Process Node:** 8nm  
- **Modem:** Snapdragon X15 LTE  
- **Memory Controller:** LPDDR4X support  
- **ISP:** Spectra 350L  
- **AI Engine:** 5th Gen Qualcomm AI Engine  

### **Memory & Storage**
- **RAM:** 4GB LPDDR4X  
- **Storage:** 32GB eMMC  

### **Physical Dimensions & Weight**
The AI Pin is split into two magnetically joined pieces — the **Pin unit** (the main computer and projector) and the **Battery Booster** (the back piece that holds extra charge and keeps everything secured through clothing).

- **AI Pin (main unit):**
  - **Weight:** 34.2 g
  - **Dimensions:** 44.50 mm × 47.50 mm × 14.98 mm
  - **Projector Module:** 19.33 mm × 9.42 mm
  - **Thinnest Point:** 8.25 mm
- **Battery Booster:**
  - **Weight:** 20.5 g
  - **Dimensions:** 45.20 mm × 47.16 mm × 8.25 mm
- **Build:** Aluminum frame with a **Corning Gorilla Glass Victus** touchpad (polished, with optical coatings)
- **Available Colors:** Eclipse (Super Matte Black Anodized), Equinox (Polished Silver / Black Touchpad), Lunar (Polished Silver / White Touchpad)

### **Battery**
The AI Pin uses a **perpetual power system** — the Battery Booster can be hot-swapped while the device remains powered on, meaning you can technically run it indefinitely with spare boosters.

- **Type:** Built-in rechargeable lithium-ion polymer battery  
- **Charging Method:** Wireless (proprietary Humane charging pad); also charged via the included charging case  
- **Battery Life:** ~4–5 hours of active use (Pin unit only)  
- **Charging Case:** Charges both the Pin and a Battery Booster simultaneously; accepts USB-C input  

### **Cellular Connectivity**
- **Dual Antenna MIMO**  
- **FDD‑LTE Bands:** 1, 2, 3, 4, 5, 7, 8, 12, 17, 20, 26, 66, 71  
- **TDD‑LTE Bands:** 38, 41  
- **UMTS/HSPA+/DC-HSDPA Bands:** 850, 900, 1700/2100, 1900, 2100 MHz  
- **Voice Support:** VoLTE, 3G  
- **SIM:** eSIM (was locked to Humane's T-Mobile MVNO; can be reprogrammed)  

### **Wi-Fi & Bluetooth**
- **Wi-Fi:** Wi-Fi 5 (802.11ac), 2.4GHz + 5GHz  
- **Bluetooth:** Bluetooth 5.1  
  - **Supported Codecs:** SBC, AAC, LDAC, aptX™ HD  
  - **Supports common Bluetooth headsets and speakers**  

### **Location Services**
- **Satellite Navigation:** GPS, GLONASS, Galileo, BeiDou  
- **Additional:** Wi-Fi Positioning System, Assisted GPS  

### **Camera**
The AI Pin has a single ultra-wide camera on its face, intended for on-demand captures triggered by gesture — not passive or always-on.

- **Photo Resolution:** 13MP (4160 × 3120 px)  
- **Video Resolution:** 1080p @ 30fps  
- **Type:** Ultra Wide Camera  
- **FOV:** 120°  
- **Aperture:** f/2.4  
- **Lens:** 5-element with single glass element  
- **Focal Distance:** 40 cm to Infinite  

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
The AI Pin's speaker — called the **Personic Speaker** — uses a Head Related Transfer Function (HRTF) to create a localized bubble of sound around the wearer, audible to them at a fixed distance without significantly leaking to surroundings.

- **Microphone:** Dual microphone array  
- **Speaker:** Built-in Personic Speaker (HRTF-based directional audio)  
- **Speaker Audio Codec:** AAC  
- **Bluetooth Audio Codecs:** SBC, AAC, LDAC, aptX™ HD  
- **Voice Calling:** VoLTE, 3G  

### **Laser Projection System aka Display**
The laser display — called the **Laser Ink Display** — projects a green image onto the user's palm and is designed to track exclusively to hand movements. It is not a traditional screen.

- **Resolution:** 720p  
- **Technology:** Laser Beam Scanning (LBS) — MEMS-based micro-electromechanical scanning projector  
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
The AI Pin has two separate LED systems for feedback. The **Trust Light** is a transparency feature — it is always visible to bystanders when any sensor is active.

- **Trust Light:** Light bar with 3 RGB LEDs — indicates Capture, Phone, Mic, Scan, and Powering On states  
- **Beacon:** Single RGB LED — silent pulse for incoming calls, messages, thermal alerts, and booster status  

### **Input & Interaction**
The touchpad surface is made from **Corning Gorilla Glass Victus** and supports capacitive touch. The device has no buttons — all input is through gesture, touch, or voice.

- **One-Finger Gestures:**
  - Tap & Hold — Voice input  
  - Double Tap — Answer/end call or start/stop music  
  - Swipe Left/Right — Previous/next track  
  - Drag Up/Down — Volume  
- **Two-Finger Gestures:**
  - Tap & Hold — Translation mode  
  - Double Tap — Take photo  
  - Double Tap & Hold — Record video  

### **Wearability & Magnet System**
The AI Pin attaches to clothing via a custom magnetic array. The front unit (Pin) and back unit (Battery Booster) sandwich the fabric between them and self-align magnetically.

- **Magnetic System:** Custom-designed magnetic array, self-aligning  
- **Compatible Fabric Thickness:** Ultrathin through Thicker (five levels)  
- **Additional Accessories:** Latch (for lightweight or delicate fabrics), Clip (for thicker materials, straps, and bags)  

### **Environmental Specifications**
- **Operating Temperature:** 5°C to 35°C (41°F to 95°F)  
- **Operating Altitude:** Up to 10,000 feet (3,000 meters); rated for use in pressurized aircraft cabins  

---

## **Software Specifications**

### **Operating System**
The AI Pin runs **CosmOS** — Humane's custom Android-based OS built around AI interaction rather than traditional app-launching. It has no home screen, no app drawer, and no notification shade in the conventional sense.

- **OS:** CosmOS (based on Android)  
  - Android 12 (System/Product)  
  - Android 11 (Vendor)  
- **Kernel:** Linux 4.14 (Version: 4.14.190) (based on Qualcomm tag)  

### **CosmOS Architecture**
CosmOS is structured around an **Ai Bus** — a core orchestration layer that intercepts user input and routes it to the appropriate AI agent or on-device process, bypassing the traditional concept of opening and managing apps.

- **Ai Bus:** Central AI routing layer — handles all requests and delegates to the appropriate agent  
- **Agents:** Modular AI programs handling weather, news, music, vision, messaging, translation, task planning, and more  
- **LLM Integration:** Cloud-connected; leveraged GPT-4 and other models via partnerships with Microsoft and OpenAI  
- **Multimodal Input:** Voice, touch, gesture, and vision — all usable in combination within a single interaction  
- **Management Portal:** `humane.center` — web app for viewing captured photos, videos, notes, and device settings (offline as of February 28, 2025)  

### **Privacy & Security**
- **Trust Light:** Always-on hardware indicator — physically impossible to use the camera or microphone without it being visible to those nearby  
- **Privacy Chip:** Dedicated hardware chip for on-device sensitive data processing  
- **Secure Enclave:** Hardware-level security module for credential and key storage  
- **No Always-On Listening:** The device requires a deliberate touchpad interaction to begin processing voice input  

### **Current Status**
- Humane shut down all services on **February 28, 2025**  
- **HP acquired** Humane's CosmOS software, 300+ patents, and the core team for **$116 million**  
- All cloud-dependent features (AI processing, cellular data, calls via Humane's network) are non-functional on stock firmware  
- All user data stored on Humane's servers was permanently deleted at shutdown  

---

The AI Pin was designed to work with cloud-based AI services, but since it's just another Android device, we can modify it to run software like [CipherOS](https://github.com/CipherOS) or LineageOS on it. This document serves as a reference for developers and enthusiasts interested in reviving the Humane AI Pin.
