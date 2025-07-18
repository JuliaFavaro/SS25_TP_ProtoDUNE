# Julia Favaro's Project - CERN Summer Student 2025, Neutrino group
## TPs' analysis for the LArTPC performances
  
This project will focus on comparing sensitivity thresholds, noise characteristics, detector response, and background rates between real and simulated ProtoDUNE data, focusing particularly on Argon-39, as part of the Offline Trigger Analysis.

Indico webpage of the 2025's program: [https://indico.desy.de/event/44862/](https://summerstudent.web.cern.ch/2025)

### Description of the project
-indicate the actual idea behind this project

#### For further information
-eventual bibliography

### Project structure
- 'MC_data.ipynb': This notebook contains analysis and visualization routines for simulated ProtoDUNE MC data. It focuses on comparing MC data properties with detector response to it, including sensitivity, noise, and background rates.

- 'RUN_test.ipynb': Main analysis notebook for cosmic runs. Includes routines for pileup extraction, visible energy quantification, dead channel identification, and plotting.

### Usage
Python  (Conda) environment to run the notebooks. We used the library Uproot to read, write and manipulate the ROOT files without installing ROOT itself.

Dataset kindly provvided by the PD Far Detector CERN EP group.

#### Dependencies 
    - numpy - array and math functions
    - uproot - for manipulating ROOT TTrees
    - awkward- for working with ragged arrays
    - scipy - numerical methods 
    - matplotlib- plotting
    - pandas- for working with datasets structures

### Authors and acknowledgment
Julia Favaro: I am a master's student at the University of Pisa (Italy), specializing in astroparticle physics and data analysis. In July and August 2025, I participated in the CERN Summer Student Program, working with the Neutrino group on the Proto-DUNE project.

Supervisors: Dr. Klaudia Wawroska, Alessandro Thea, Giovanna Lehmann Miotto (EP-DUNE Department). 
  
### Project status
My summer student program finishes on 22.08.2025.