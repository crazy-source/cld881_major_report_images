# Folder: 20 - Volume Fraction Visualization Series

## Overview
This folder contains a time-series sequence of Computational Fluid Dynamics (CFD) simulation results showing the evolution of gas-liquid two-phase flow with volume fraction (vf) distribution inside the computational domain.

## Simulation Configuration
- **Configuration Identifier**: 60_2
- **Total Images**: 19 snapshots
- **Time Step Range**: 0 to 437 (increments of 25, with final step at 437)
- **File Naming Pattern**: `vf-inside-60_2_XXXX.png` where XXXX is the time step number

## Image Content Description

### What Each Image Shows
Each image displays a **volume fraction contour plot** of phase-2 (gas phase) within a vertical rectangular computational domain. The visualization uses ANSYS Fluent 2025 R1 STUDENT software.

### Key Visual Elements:

1. **Color-Coded Volume Fraction Distribution**:
   - **Blue regions** (volume fraction ≈ 0.00): Represent the continuous liquid phase (phase-1) where no gas is present
   - **Red regions** (volume fraction ≈ 0.60): Represent high concentration of gas phase (phase-2)
   - **Intermediate colors** (yellow, green, light blue): Represent transition zones with mixed phases or gas-liquid interfaces

2. **Domain Structure**:
   - Tall, narrow rectangular domain (vertical orientation)
   - Sharp horizontal interface separating gas-rich (bottom) and liquid-rich (top) regions
   - Thin multi-colored transition band at the phase boundary indicating the gas-liquid interface

3. **Temporal Evolution**:
   - **Initial state** (0000): Shows initial conditions, likely with gas starting to accumulate at the bottom
   - **Early stages** (0025-0100): Gas injection and bubble formation begin
   - **Mid stages** (0125-0200): Bubble growth and interface development
   - **Later stages** (0225-0400): Continued gas accumulation and interface evolution
   - **Final state** (0425-0437): Final configuration showing gas distribution at the end of the simulation

### Physical Interpretation
These images capture the **pulse injection** of gas into a liquid-filled domain. The sequence shows:
- Gas phase accumulation at the bottom of the domain
- Formation and evolution of the gas-liquid interface
- Distribution of volume fraction throughout the domain over time
- Response of the system to the pulsed inlet condition

### Technical Details
- **Visualization Type**: Volume fraction contour plot (phase-2)
- **Software**: ANSYS Fluent 2025 R1 STUDENT
- **Coordinate System**: 3D domain with X, Y, Z axes indicated
- **Color Scale**: Volume fraction range from 0.00 (blue) to 0.601 (red)

## Usage
These images are useful for:
- Analyzing bubble formation and growth dynamics
- Understanding gas injection patterns during pulse injection
- Visualizing phase distribution evolution over time
- Comparing different time steps to observe temporal changes
- Documenting simulation results for reports and presentations

## Image Sequence
The images are numbered sequentially by time step, allowing for:
- Frame-by-frame analysis of bubble dynamics
- Creation of animation sequences
- Identification of key events (bubble formation, interface development, etc.)
- Correlation with quantitative data (flow rates, bubble volumes, etc.)

