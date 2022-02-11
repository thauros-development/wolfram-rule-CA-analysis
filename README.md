## Wolfram Cellular Automata Study

A deep analysis and result visualization of a Wolfram Rule Automata.

The notebook is written in python, but fully automatized and no programming experience is needed to change rules for analysis.

The notebook is generic and can be used for general time-series.


Run the notebooks directly on google colab: 

*Rule 30 proof* : [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Brg_Uw2Xk_UO5bEjggE98jmulHgaDSsl?usp=sharing)


*Analysis Notebook - basic* : [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GaF1YIa77VqiOfO88-CES006TCTgvFlY?usp=sharing)
- CA generation algorithm
- Modification for gathering rule frequencies
- Signal Plots
- Kernel Plot (Frequency Tail)
- Statistical Descriptives (Mean, Standard Deviation and Standard Error of Mean)
- Frequency Analysis (FFT)
    - Amplitude-Frequency Plot / Powerspectrum
    - Phase Angles
    - Phase Spectrum
    - Chaos analysis
    - Lyapunov Exponents
    - Sample Entropy
    - Hurst Exponent
    - Correlation Dimension
    - Detrended Fluctuation Analysis
- Phase Diagram / 3d-Poincaré plot

*Analysis Notebook - full* : [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pey1ydgsQkw_gQs4WWRRh1eo_Z4oXmK9?usp=sharing)

This notebook implements in addition to previous methods:
- UMAP (t-SNE)
- Spectogram
- Oscilloscope
- Coherence
- Stationarity
- Granger-Causality
- SARIMAX

