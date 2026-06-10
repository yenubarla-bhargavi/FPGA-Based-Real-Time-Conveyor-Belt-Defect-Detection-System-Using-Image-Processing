# FPGA-Based-Real-Time-Conveyor-Belt-Defect-Detection-System-Using-Image-Processing
Designed and simulated an FPGA-based real-time conveyor belt defect detection system using Verilog/VHDL in Quartus Prime. The system processes image pixel data, performs grayscale-based analysis, extracts features, and detects defects through threshold comparison, demonstrating FPGA-based industrial inspection and automation concepts.

# FPGA-Based Real-Time Conveyor Belt Defect Detection System

## Overview

This project presents an FPGA-based real-time conveyor belt defect detection system designed for industrial automation applications. The system processes image pixel data and identifies defects in moving objects using image processing techniques implemented in Verilog/VHDL.

The design was developed and verified through simulation using Intel Quartus Prime.

---

## Objectives

- Detect defects in conveyor belt objects.
- Perform grayscale-based image analysis.
- Implement threshold-based defect detection.
- Simulate real-time inspection using FPGA logic.
- Verify functionality through waveform analysis.

---

## Features

- FPGA-based architecture
- Real-time image processing
- Grayscale image analysis
- Threshold comparison
- Shape and size inspection
- Defect detection logic
- Quartus Prime simulation
- Verilog/VHDL implementation

---

## System Architecture

Input Image Data Module
        ↓
Image Processing Module
        ↓
Threshold Processing
        ↓
Feature Extraction
        ↓
Defect Detection Module
        ↓
Output Module

---

## Modules

### Input Image Data Module
Provides image pixel data for processing.

### Image Processing Module
Converts image information into a suitable format for analysis and extracts useful features.

### Threshold Processing Module
Compares pixel values with predefined threshold values.

### Feature Extraction Module
Extracts shape, size, area, and edge information.

### Defect Detection Module
Determines whether the object is defective based on extracted features.

### Output Module
Generates the final defect status signal.

---

## Tools Used

- Intel Quartus Prime
- Verilog/VHDL
- ModelSim (Simulation)
- FPGA Design Methodology

---

## Applications

- Industrial Automation
- Manufacturing Inspection
- Conveyor Belt Monitoring
- Quality Control Systems
- Machine Vision Systems

---

## Results

Successfully simulated and verified the defect detection system using Quartus Prime waveform analysis. The system correctly identified defective and non-defective objects based on predefined inspection criteria.

Author
Bhargavi
