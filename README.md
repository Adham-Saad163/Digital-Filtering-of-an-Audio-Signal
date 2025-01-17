# Digital Filtering of an Audio Signal

## Overview
This project involves designing and implementing digital FIR filters using different methodologies and applying them to a practical audio signal filtering problem. The tasks include creating a custom filter design tool and using it to filter an audio signal contaminated with sinusoidal interference.

## Features

### Part 1: FIR Filter Design Tool
- Implemented **Windowed Sinc**, **Least Squares (LS)**, and **Weighted LS (WLS)** FIR filter design methods.
- Supported user inputs:
  - Filter length
  - Sampling frequency
  - Cutoff frequency
  - Display scale (linear or logarithmic)
- Compared filter performance using different window functions:
  - **Rectangular**
  - **Blackman**
  - **Chebyshev**
  - **Kaiser**
- Plotted and analyzed the magnitude response for each filter.

### Part 2: Practical Filtering Application
- Processed an audio signal using the designed FIR filter tool:
  1. Read and upsampled the audio signal.
  2. Added sinusoidal interference at a specified frequency.
  3. Designed and iteratively refined a digital FIR filter to attenuate interference.
  4. Filtered the audio signal and analyzed its frequency spectrum before and after filtering.
  5. Evaluated audio quality by listening to the filtered signal.

## Results

### FIR Filter Design Observations
- **Rectangular Window:** Sharp transitions but high side lobe levels.  
- **Blackman Window:** Excellent side lobe suppression with a wider transition band.  
- **Chebyshev Window:** Trade-off between ripple and stopband attenuation.  
- **Kaiser Window:** Flexible trade-offs via the beta parameter.  

### Practical Filtering Observations
- **Interference Frequency:** 15 kHz, far from the original signal frequencies (0–11 kHz).  
- **Filter Design:** Kaiser window with a length of 51 taps provided the best performance.  
- **Audio Quality:** The interference was effectively removed without significant distortion of the original signal.  

## Contributors
- **Adham Saad**  
  Email: [s-adham.saad@zewailcity.edu.eg](mailto:s-adham.saad@zewailcity.edu.eg)  

- **Amr Ahmed**  
  Email: [s-amr.abdelnaby@zewailcity.edu.eg](mailto:s-amr.abdelnaby@zewailcity.edu.eg)  

- **Eyad Hany**  
  Email: [s-eyad.sharaf@zewailcity.edu.eg](mailto:s-eyad.sharaf@zewailcity.edu.eg)  

- **Khaled Ashraf**  
  Email: [s-khaled.mousa@zewailcity.edu.eg](mailto:s-khaled.mousa@zewailcity.edu.eg)    
