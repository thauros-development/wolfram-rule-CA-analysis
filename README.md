## Wolfram Cellular Automata Study

A deep analysis and result visualization of a Wolfram Rule Automata.

The notebook is written in python, but fully automatized and no programming experience is needed to change rules for analysis.
All CA Rules are listed in the Wolfram Atlas for Simple Programs: [[Link]](http://atlas.wolfram.com/01/01/) 

The notebook is generic and can be used for general time-series.

#### *Rule 30 proof* : [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Brg_Uw2Xk_UO5bEjggE98jmulHgaDSsl?usp=sharing)
Including Cellular Automata Generation Algorithm and Visualizations

(Rule 30 on Wikipedia [[Link]](https://en.wikipedia.org/wiki/Rule_30), Rule 30 Prize Problems [[Link]](https://writings.stephenwolfram.com/2019/10/announcing-the-rule-30-prizes/https://writings.stephenwolfram.com/2019/10/announcing-the-rule-30-prizes/))


#### *CA Analysis Notebook - Basic* : [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GaF1YIa77VqiOfO88-CES006TCTgvFlY?usp=sharing)
- Cellular Automata Generation Algorithm
- Signal Plots
- Kernel Plot (Frequency Tail)
- Statistical Descriptives  
    - Mean
    - Standard Deviation 
    - Standard Error of Mean
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

#### *CA Analysis Notebook - Full* : [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pey1ydgsQkw_gQs4WWRRh1eo_Z4oXmK9?usp=sharing)

This notebook is slightly less polished and implements in addition:
- Dummy Signals for Referencing
    - Basic Sinusodial Signals with and without Harmonic Content
    - Logistic Function for Chaotic (Edge-of-chaos) Content
- UMAP (t-SNE) Multidimensional Scaling
- Spectogram
- Animated Oscilloscope
- Coherence between two Signals
- Signal Stationarity
- Granger-Causality Prediction
- SARIMAX Prediction / RMSE

