# Humane AI Pin - Hardware & Software Specifications
![image](https://github.com/user-attachments/assets/0de74a51-7001-46b7-bf76-96cc3bdf1acd)

As we know, **the Humane AI Pin is essentially a unique Android device** paired with a laser projection system. While Humane Inc. has discontinued its services, the AI Pin's hardware remains functional and capable. Below are the detailed hardware and software specifications of the device.

## **Hardware Specifications**

### **Processor**
The Humane AI Pin is powered by the **Qualcomm Atoll AB** processor, which refers to the **Qualcomm Snapdragon 720G** chipset. The **"Atoll"** is the internal codename for the **Snapdragon 720G**, and the **"AB"** variant is a specific revision of this SoC.

- **CPU:**  
  - **Qualcomm Snapdragon 720G (_SM7125)_**
  - 2x Cortex-A76 @ **2.3 GHz** (Prime & Performance Cores)  
  - 6x Cortex-A55 @ **1.8 GHz** (Efficiency Cores)  
- **GPU:** Adreno 618  
- **Process Node:** 8nm  
- **Modem:** Snapdragon X15 LTE  
- **Memory:** LPDDR4X support  
- **ISP:** Spectra 350L  
- **AI Engine:** 5th Gen Qualcomm AI Engine  

### **Memory & Storage**
- **RAM:** 4GB LPDDR4X  
- **Storage:** 32GB eMMC  

### **Cellular Connectivity**
- **Dual Antenna MIMO**  
- **FDD‑LTE Bands:** 1, 2, 3, 4, 5, 7, 8, 12, 17, 20, 26, 66, 71  
- **TDD‑LTE Bands:** 38, 41  
- **UMTS/HSPA+/DC-HSDPA Bands:** 850, 900, 1700/2100, 1900, 2100 MHz  
- **Voice Support:** VoLTE, 3G  
- **SIM:** eSIM (Locked to Humane software but can be reprogrammed)  

### **Wi-Fi & Bluetooth**
- **Wi-Fi:** Wi-Fi 5 (802.11ac) with 2.4GHz + 5GHz  
- **Bluetooth:** Bluetooth 5.1  
  - **Supported Codecs:** SBC, AAC, LDAC, aptX™ HD  
  - **Supports common Bluetooth headsets and speakers**  

### **Location Services**
- **Satellite Navigation:** GPS, GLONASS, Galileo, BeiDou  
- **Additional:** Wi-Fi Positioning System, Assisted GPS  

### **Sensors**
- **Light Sensor:** Ambient light sensor  
- **Motion Sensors:** Accelerometer and gyroscope  
- **Position Sensor:** Magnetometer + GPS  
- **3D Depth Sensor:** Indirect Time-of-Flight (iToF) Camera  
  - **FOV:** 125°  
  - **Aperture:** f/1.4  
  - **Lens:** 4-element lens  
  - **Resolution:** 640x480 px (VGA)  

### **Laser Projection System aka Display**
- **Resolution:** 720p  
- **Projection Angle:**  
  - **Horizontal:** 18.2° wide  
  - **Vertical:** 13.3° tall  
  - **Diagonal:** 22.4°  
- **Projection Size:** 7 cm x 9.6 cm at 30 cm distance  
- **Technology:** Laser-based projection  

## **Software Specifications**
- **Operating System:**
  - Android 12 (System/Product)  
  - Android 11 (Vendor)  
- **Kernel:** Linux 4.14 (Version: 4.14.190)  (based on qualcomm tag: 

The AI Pin was designed to work with cloud-based AI services, but since it's just another device, we can modify it to run software like [CipherOS](https://github.com/CipherOS) or LineageOS on it. This document serves as a reference for developers and enthusiasts interested in reviving the Humane AI Pin.

