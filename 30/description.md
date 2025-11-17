# Folder: 30 - Volume Fraction Visualization Series (High Resolution)

## Overview
This folder contains a high-resolution time-series sequence of Computational Fluid Dynamics (CFD) simulation results showing detailed evolution of gas-liquid two-phase flow with volume fraction distribution inside the computational domain.

## Simulation Configuration
- **Configuration Identifier**: 10_5
- **Total Images**: 36 snapshots
- **Time Step Range**: 0 to 350 (increments of 10)
- **File Naming Pattern**: `vf-inside-10_5_XXXX.png` where XXXX is the time step number
- **Temporal Resolution**: Higher resolution than other folders (10-step increments vs. 25-step increments)

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

3. **Temporal Evolution** (High Resolution):
   - **Initial state** (0000): Initial conditions with gas starting to accumulate
   - **Very early stages** (0010-0050): Fine-scale capture of initial bubble formation and gas injection onset
   - **Early stages** (0060-0100): Detailed bubble growth and interface development
   - **Mid stages** (0110-0200): Continued evolution with higher temporal resolution showing smooth transitions
   - **Later stages** (0210-0300): Advanced bubble dynamics and interface stabilization
   - **Final stages** (0310-0350): Final configuration showing mature gas distribution

### Physical Interpretation
These images capture the **pulse injection** of gas into a liquid-filled domain with **higher temporal resolution** than other simulation sets. The sequence shows:
- Fine-scale temporal evolution of gas phase accumulation
- Detailed bubble formation and growth dynamics
- Smooth interface development over time
- High-resolution capture of transient phenomena
- Response of the system to pulsed inlet conditions with fine time steps

### Technical Details
- **Visualization Type**: Volume fraction contour plot (phase-2)
- **Software**: ANSYS Fluent 2025 R1 STUDENT
- **Coordinate System**: 3D domain with X, Y, Z axes indicated
- **Color Scale**: Volume fraction range from 0.00 (blue) to 0.601 (red)
- **Temporal Resolution**: 10 time steps between snapshots (finer than other configurations)

## Usage
These images are particularly useful for:
- **Detailed temporal analysis** of bubble formation and growth
- **High-resolution animation** creation showing smooth transitions
- **Fine-scale dynamics** study of gas injection patterns
- **Transient behavior** analysis during pulse injection
- **Comparative studies** with other simulation configurations
- **Quantitative analysis** correlation with time-dependent measurements

## Advantages of High Resolution
The 10-step increment provides:
- **Smoother animations** when creating video sequences
- **Better capture** of rapid transient events
- **More data points** for quantitative analysis
- **Enhanced detail** in bubble dynamics visualization
- **Improved correlation** with experimental or analytical data

## Image Sequence
The images are numbered sequentially by time step with fine increments, allowing for:
- Frame-by-frame analysis with high temporal resolution
- Creation of smooth animation sequences
- Identification of rapid transient events
- Detailed correlation with quantitative time-series data
- Precise timing of bubble formation and interface development

