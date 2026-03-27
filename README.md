
# Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Aim
To analyze and evaluate the performance of an optical communication system by studying the relationship between fiber length, received power, Q factor and Bit Error Rate(BER) and to observe changes in the eye diagram with increasing fiber length using optiperformer.

---

## Theory

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Observation

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---
## Block Diagram
<img width="736" height="388" alt="image" src="https://github.com/user-attachments/assets/7f0776fd-e602-470b-b936-e735e3235040" />


## Tabulation

**Transmission Analysis Across Fiber Lengths**

## Transmission Analysis Across Fiber Lengths

| S.No | Fiber Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
|-----|------------------|----------------------|--------------------|-------------|---------|------------|------------------------------------|
| 1 | 60  | 30.563 | 15.148 | 85.0711 | 0 | 6.09879e-05 | 0.546875 |
| 2 | 70  | 18.914 | 17.219 | 66.7481 | 0 | 3.8153e-05 | 0.546875 |
| 3 | 80  | 11.776 | 17.289 | 61.3449 | 0 | 2.39016e-05 | 0.546875 |
| 4 | 90  | 7.801  | 21.079 | 44.5452 | 0 | 1.48427e-05 | 0.546875 |
| 5 | 100 | 4.422  | 23.679 | 45.2504 | 0 | 9.42485e-06 | 0.546875 |

![WhatsApp Image 2026-01-24 at 1 29 05 PM](EXP6.jpeg)

# Graph

<img width="879" height="323" alt="image" src="https://github.com/user-attachments/assets/ec9ffcf3-76ad-4546-9c5e-d81e140c7fb0" />

---

## RESULT

Thus the optiperformer has been installed successfully and sample file has been run
