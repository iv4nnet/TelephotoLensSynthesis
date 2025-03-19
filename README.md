# Teleobjective Synthesis

## Overview
This repository contains a course assignment for the “Automated Optical System Design” course at BMSTU. The project involves synthesizing a teleobjective optical system using a Galilean telescopic system (ТСГ) combined with a focusing objective (ФО). The goal is to design an optical system that meets specific performance criteria while maintaining a compact form factor.

## Project Description
The assignment focuses on the synthesis of an optical system with the following characteristics:
- **Angular Field:** The system is designed with an angular field of 2W = 1°.
- **Relative Aperture:** The target aperture ratio is 1:5.
- **Sensor Parameters:** The sensor has a diagonal of 6 mm and an element size of 5 μm.
- **System Length:** The overall length of the synthesized system is 347 mm, which is less than its focal length of 365 mm.

The design approach involves two main components:

### 1. Galilean Telescopic System (ТСГ)
- **Function:**  
  - Transforms a small input angular field into a moderate angular field suitable for the focusing objective.
  - Corrects aberrations introduced by the focusing system.
- **Design Considerations:**  
  - Consists of two components: a positive lens (first component) and a negative lens (second component).
  - Special care is taken to balance the optical power and control aberrations, such as spherical aberration and chromatic aberration.

### 2. Focusing Objective (ФО)
- **Function:**  
  - Acts as a fast (bright) objective that forms the final image.
- **Design Components:**  
  - The focusing objective is based on a multi-element design that may include a two-lens cemented group, a thick meniscus, and a Smith lens.
  - The objective must achieve a high resolution with an adequate Modulation Transfer Function (MTF) while maintaining a compact design.

## Synthesis and Optimization
The synthesis process includes:
- **Initial Design:**  
  Starting with known parameters (angular field, focal length, sensor specifications), an initial design for a teleobjective is established.
- **Optimization:**  
  The system is optimized—often using optical design software (e.g., Zemax)—to minimize aberrations and meet performance criteria such as:
  - A final focal length of approximately 365 mm.
  - A relative aperture of 1:5.
  - An image diameter of 6 mm.
  - A total system length of around 347 mm, which is less than the focal length.
  - A Modulation Transfer Function (MTF) of at least 0.5 at the designated spatial frequency.

## Final System Parameters
The synthesized teleobjective meets the following key specifications:
- **Angular Field:** 2W ≈ 1°
- **Focal Length (f’):** 365 mm
- **Relative Aperture:** 1:5
- **MTF:** ≥ 0.5 at the specified spatial frequency
- **Image Diameter:** 6 mm
- **Number of Lenses:** 8 elements
- **Total System Length:** 347 mm (which is less than the focal length)

## Getting Started
To explore or modify this project:
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/iv4nnet/TeleobjectiveSynthesis.git
   ```
2. **Review the Documentation:**  
   The project report (provided in the PDF) contains a detailed explanation of the synthesis process, design parameters, and optimization results.
3. **Run the Design Software:**  
   If applicable, replicate the design and optimization using your preferred optical design tool (Zemax) to further analyze and refine the system.

## Technologies and Tools
- **Optical Design Software:** Zemax for simulation and optimization.
- **Calculation Methods:** Detailed Mathcad calculations and theoretical synthesis based on optical design principles.
- **Documentation:** Prepared using Microsoft Word, with design parameters and optimization results clearly outlined.
