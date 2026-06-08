# Seismic Signal Noise Reduction (FFT-Based)
FFT-based seismic noise reduction using MATLAB Simulink with real earthquake data from USGS.
## Overview
This project was developed as part of my Digital Signal Processing (DSP) Laboratory coursework. 
It demonstrates how seismic signals can be processed in MATLAB Simulink to reduce high-frequency ground noise using FFT-based spectral analysis and lowpass filtering.
## Dataset
- Source: [USGS Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/search/)
- Data: Real seismic event records used as input for simulation and analysis.
## Workflow
1. Import seismic dataset from USGS.
2. Simulate raw seismic signal.
3. Add high-frequency ground noise.
4. Perform FFT spectrum analysis.
5. Apply lowpass filter for noise reduction.
6. Compare noisy vs. filtered signals in time and frequency domains.
## Features
- Real-time simulation of seismic signals
- FFT-based spectral analysis
- Lowpass filtering for noise reduction
- Clear visualization of noisy vs. filtered signals
- Modular Simulink design for easy extension
## Applications
- Seismic signal processing
- Earthquake detection and analysis
- Noise reduction in DSP systems
## Tools & Environment
- MATLAB Simulink
- DSP Toolbox
- FFT-based spectral analysis
## Results
- Noisy Signal Spectrum (FFT) shows high-frequency interference.
- Filtered Signal Spectrum (FFT) demonstrates effective noise reduction.
- Time-domain comparison highlights the clarity of the filtered seismic signal.
## Future Work
- Integration with real-time seismic monitoring systems
- Adaptive filtering for varying noise conditions
- Expansion to multi-channel seismic datasets
