# **Function Generator Circuit**  

## **Project Overview**  
This project involves the design and implementation of a **function generator circuit** that produces **square, sine, and triangular waveforms**. The circuit is built using **LM741 operational amplifiers**, with a **diode-based sine wave shaper**. The output frequency is controlled by varying **resistor values**, ensuring a stable **frequency bandwidth**.  

A **Printed Circuit Board (PCB) layout** has been designed to enhance performance by minimizing noise and ensuring reliability.  

## **Objectives**  
- Generate **square, sine, and triangular waveforms** using operational amplifiers.  
- Achieve a **wide frequency bandwidth** by varying resistor values.  
- Design and implement a **PCB layout** to improve signal stability and minimize noise.  

## **Circuit Design**  
The circuit consists of three main sections:  
- **Square Wave Generator** (Astable Multivibrator using LM741).  
- **Triangular Wave Generator** (Integrator circuit using LM741).  
- **Sine Wave Shaper** (Diode-based network for waveform smoothing).  

## **Simulation & Results**  
- **Simulation performed using LTSpice/Proteus** (Specify the tool used).  
- **FFT Analysis** confirms waveform accuracy and expected frequency response.  
- **Observed Frequency Range:** 600 Hz – 36.8 kHz.  

### **Theoretical vs. Simulated Results**  
| Method      | Frequency (kHz) |  
|------------|---------------|  
| Theoretical | 1.163 kHz |  
| Simulated (FFT) | 1.78 kHz |  

## **PCB Design**  
The PCB layout was designed in **EasyEDA/KiCad** (Specify the tool used) to ensure minimal noise and signal distortion.  

## **Repository Structure**  
```
Function-Generator  
│── README.md  (This file)  
│── Images_Files
│── Simulation_Files/  (LTSpice, Proteus, etc.)  
│── Gerber_Files/  (For PCB fabrication)  
│── BOM.csv  (Bill of Materials)  
```  

## **Future Improvements**  
- Integrate **microcontroller-based digital control** for automated frequency selection.  
- Optimize component selection for **higher frequency accuracy**.  
- Improve waveform shaping techniques to **reduce distortion**.  

## **References**  
- [Function Generator Based on Circuit Simulation](https://www.researchgate.net/publication/370579097_Function_Generator_Based_on_Circuit_Simulation_Method)  
- [Waveform Generator Using Op-Amp](http://ee.cet.ac.in/downloads/Notes/ECLab/10-Waveform%20Generator%20Using%20OpAmp.pdf)  

## **Download & Access**  
Project files, including the simulation and Gerber files, can be accessed at:  
[Click here](https://drive.google.com/drive/folders/1kJx_mJMqGXgGpYxI_YRqGAKUDS1veTCE?usp=drive_link)  

---
