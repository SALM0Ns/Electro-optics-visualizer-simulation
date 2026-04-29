

# Electro-Optics Visualizer Simulation
### Interactive Learning Lab for Gen 3 Unfilmed Technology

This repository features a pair of interactive web-based simulators designed to visualize the complex quantum physics and engineering inside **Generation 3 Image Intensifier Tubes (IIT)**. 

---

## Project Overview
Understanding how photons are converted into a visible image in total darkness is a challenge. This project aims to bridge that gap by providing a real-time particle simulation of the "Photon-to-Electron" journey.

### We provide two distinct iterations of the simulator:

blob:https://gemini.google.com/ee5c4e68-5eb4-48a7-985e-8c0da4c43d10

#### **Version 1: The Tactical Lab (High-Contrast Red)**
* **Focus:** Technical performance and hardware comparison.
* **Key Feature:** Dynamic **Signal-to-Noise Ratio (SNR)** readout and precise toggling between legacy **Thin-Film** and modern **Unfilmed** architecture.
* **Visuals:** High-contrast interface optimized for identifying the "Ion Barrier Film" bottleneck.

blob:https://gemini.google.com/18ccad06-ef57-434d-9597-13ab5ab5ebae

#### **Version 2: The Quantum Pipeline (Blueprint Blue)**
* **Focus:** Structural flow and component architecture.
* **Key Feature:** Clear visualization of the **Quantum Physics Pipeline**, emphasizing the path from the Objective lens through the GaAs Photocathode to the Eyepiece.
* **Visuals:** Clean, grid-based laboratory aesthetic for educational clarity.

---

##  Educational Features
* **Particle Avalanche Simulation:** Watch how a single electron multiplies exponentially within the **Microchannel Plate (MCP)**.
* **Phosphor Screen Comparison:** Toggle between **P43 (Green)** and **P45 (White)** phosphor to see how spectral output affects user perception.
* **Light Level Dynamics:** Adjust ambient light from "Starlight" to "Moonlight" and observe how the tube reacts to photon scarcity.
* **The "Film" Effect:** Observe how an Aluminum Oxide film blocks up to 40% of photoelectrons, creating "Scintillation" (visual noise).

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
