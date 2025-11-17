# Folder: 30_2D - 2D Volume Fraction Visualization Series

## Overview
This folder contains a time-series sequence of Computational Fluid Dynamics (CFD) simulation results showing the evolution of gas-liquid two-phase flow in a **2D simulation configuration**. The images display volume fraction (vf) distribution inside the computational domain.

## Simulation Configuration
- **Configuration Identifier**: 30_2
- **Simulation Type**: 2D (Two-Dimensional)
- **Total Images**: 12 snapshots
- **Time Step Range**: 0 to 270 (increments of 25, with final step at 270)
- **File Naming Pattern**: `vf-inside-30_2_XXXX.png` where XXXX is the time step number

## Image Content Description

### What Each Image Shows
Each image displays a **volume fraction contour plot** of phase-2 (gas phase) within a computational domain. The visualization uses ANSYS Fluent 2025 R1 STUDENT software. This is a **2D simulation**, meaning the domain represents a cross-sectional view or a simplified 2D representation of the flow.

### Key Visual Elements:

1. **Color-Coded Volume Fraction Distribution**:
   - **Blue regions** (volume fraction ≈ 0.00): Represent the continuous liquid phase (phase-1) where no gas is present
   - **Red regions** (volume fraction ≈ 0.60): Represent high concentration of gas phase (phase-2)
   - **Intermediate colors** (yellow, green, light blue): Represent transition zones with mixed phases or gas-liquid interfaces

2. **Domain Structure** (2D):
   - Rectangular domain representing a 2D cross-section
   - Gas-liquid interface visible as a color transition boundary
   - Simplified geometry compared to full 3D simulations
   - Computational efficiency advantage over 3D simulations

3. **Temporal Evolution**:
   - **Initial state** (0000): Shows initial conditions in 2D domain
   - **Early stages** (0025-0100): Gas injection and bubble formation in 2D
   - **Mid stages** (0125-0200): Bubble growth and interface development
   - **Later stages** (0225-0270): Continued gas accumulation and interface evolution

### Physical Interpretation
These images capture the **pulse injection** of gas into a liquid-filled domain using a **2D simulation approach**. The sequence shows:
- Gas phase accumulation and distribution in 2D
- Formation and evolution of the gas-liquid interface
- 2D bubble dynamics and shape evolution
- Simplified but computationally efficient representation of the flow

### Technical Details
- **Visualization Type**: Volume fraction contour plot (phase-2)
- **Software**: ANSYS Fluent 2025 R1 STUDENT
- **Simulation Dimension**: 2D (Two-Dimensional)
- **Coordinate System**: 2D domain representation
- **Color Scale**: Volume fraction range from 0.00 (blue) to 0.601 (red)

## Advantages of 2D Simulation
- **Computational Efficiency**: Faster simulation times compared to 3D
- **Simplified Analysis**: Easier to interpret and analyze flow patterns
- **Reduced Complexity**: Lower computational resource requirements
- **Rapid Prototyping**: Quick testing of simulation parameters
- **Educational Value**: Clear visualization of fundamental flow phenomena

## Usage
These images are useful for:
- **2D flow pattern analysis** and visualization
- **Computational efficiency studies** comparing 2D vs 3D results
- **Fundamental bubble dynamics** understanding in simplified geometry
- **Parameter studies** requiring multiple simulation runs
- **Educational purposes** demonstrating two-phase flow concepts
- **Validation studies** comparing with analytical or simplified models

## Comparison with 3D Simulations
When compared to 3D simulation results:
- **Simplified representation** of complex 3D phenomena
- **Faster computation** allows for more time steps or parameter variations
- **Easier visualization** of core flow mechanisms
- **Limitations**: May not capture all 3D effects such as:
  - Lateral spreading
  - Three-dimensional bubble shapes
  - Complex 3D flow structures

## Image Sequence
The images are numbered sequentially by time step, allowing for:
- Frame-by-frame analysis of 2D bubble dynamics
- Creation of 2D animation sequences
- Identification of key events in simplified geometry
- Correlation with 2D quantitative data
- Comparison with corresponding 3D simulation results

