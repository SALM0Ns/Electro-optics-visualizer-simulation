

# Electro-Optics Visualizer Simulation
### Interactive Learning Lab for Gen 3 Unfilmed Technology

This repository features a pair of interactive web-based simulators designed to visualize the complex quantum physics and engineering inside **Generation 3 Image Intensifier Tubes (IIT)**. 

---

## Project Overview
Understanding how photons are converted into a visible image in total darkness is a challenge. This project aims to bridge that gap by providing a real-time particle simulation of the "Photon-to-Electron" journey.

### We provide two distinct iterations of the simulator:


#### **Version 1: The Tactical Lab (High-Contrast Red)**
* **Focus:** Technical performance and hardware comparison.
* **Key Feature:** Dynamic **Signal-to-Noise Ratio (SNR)** readout and precise toggling between legacy **Thin-Film** and modern **Unfilmed** architecture.
* **Visuals:** High-contrast interface optimized for identifying the "Ion Barrier Film" bottleneck.

<img width="1470" height="832" alt="Screenshot 2569-04-29 at 22 03 27" src="https://github.com/user-attachments/assets/ddef1e30-46b6-494f-adf5-5556c7482484" />
<img width="1470" height="828" alt="Screenshot 2569-04-29 at 22 03 34" src="https://github.com/user-attachments/assets/c3997b0e-db29-4150-8fb9-467cd983d80c" />
<img width="1464" height="816" alt="Screenshot 2569-04-29 at 22 04 15" src="https://github.com/user-attachments/assets/8c629cdb-b6fd-4b3e-8e32-81c8a2a2528e" />
<img width="1470" height="833" alt="Screenshot 2569-04-29 at 22 04 22" src="https://github.com/user-attachments/assets/71cc3bf9-3138-4e9c-8793-3226a0e00342" />

---

#### **Version 2: The Quantum Pipeline (Blueprint Blue)**
* **Focus:** Structural flow and component architecture.
* **Key Feature:** Clear visualization of the **Quantum Physics Pipeline**, emphasizing the path from the Objective lens through the GaAs Photocathode to the Eyepiece.
* **Visuals:** Clean, grid-based laboratory aesthetic for educational clarity.
* **The "Film" Effect:** Observe how an Aluminum Oxide film blocks up to 40% of photoelectrons, creating "Scintillation" (visual noise).
<img width="1470" height="830" alt="Screenshot 2569-04-29 at 22 03 43" src="https://github.com/user-attachments/assets/351a7724-4b3a-4852-9287-e77e8c70e6b4" />
<img width="1470" height="830" alt="Screenshot 2569-04-29 at 22 03 52" src="https://github.com/user-attachments/assets/85597f19-91f1-4b2a-9108-487759bd630f" />

---

##  Educational Features
* **Particle Avalanche Simulation:** Watch how a single electron multiplies exponentially within the **Microchannel Plate (MCP)**.
* **Phosphor Screen Comparison:** Toggle between **P43 (Green)** and **P45 (White)** phosphor to see how spectral output affects user perception.
* **Light Level Dynamics:** Adjust ambient light from "Starlight" to "Moonlight" and observe how the tube reacts to photon scarcity.


---

##  The Science Inside
The simulator accurately represents the four-stage amplification process:
1.  **GaAs Photocathode:** Photoelectric effect converting light into electrons.
2.  **Ion Barrier Film:** A physical barrier used in standard Gen 3 to protect the cathode, at the cost of sensitivity.
3.  **MCP (Microchannel Plate):** The engine of the tube, creating an electron cascade.
4.  **Phosphor Screen:** Kinetic energy is converted back into visible light.

---

##  Technical Stack
* **Engine:** HTML5 Canvas API
* **Styling:** CSS3 (Tactical/Modern UI Design)
* **Logic:** Vanilla JavaScript (Physics & Particle systems)
* **Architecture:** Modular design for easy expansion into "Auto-gating" or "Halo" simulations.

## ⚖️ Disclaimer
*This project is an unofficial educational tool created for physics visualization and learning purposes. It is not affiliated with any defense contractor or manufacturer. All concepts are based on publicly available electro-optics theory.*
