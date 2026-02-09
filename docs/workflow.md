# Recommended workflow

This document describes the recommended usage order of PVMSim to ensure
consistent processing and reproducible results.

## 1. Project and Data
Load the measured I–V curve files, metadata, and the module datasheet.
All inputs must be validated before parameter extraction.

External reference ↗  
https://github.com/Liomnis/PVMSim#project-and-data

## 2. Bounds
Define and review physically meaningful lower and upper bounds for the
double-diode model parameters.

External reference ↗  
https://github.com/Liomnis/PVMSim#bounds

## 3. Parameter Extraction (Coarse + Fine)
Run the staged parameter extraction procedure, starting with a coarse
search followed by fine refinement.

External reference ↗  
https://github.com/Liomnis/PVMSim#parameter-extraction

## 4. Validation and Metrics
Evaluate model accuracy and electrical consistency using quantitative
validation metrics.

External reference ↗  
https://github.com/Liomnis/PVMSim#validation-and-metrics

## 5. Figures and Export
Generate I–V and P–V plots and export numerical results and figures for
reporting purposes.

External reference ↗  
https://github.com/Liomnis/PVMSim#figures-and-export

## 6. Batch and Report (optional)
Process multiple curves in batch mode and generate consolidated reports.
This step is recommended for comparative studies and large datasets.

External reference ↗  
https://github.com/Liomnis/PVMSim#batch-and-report

