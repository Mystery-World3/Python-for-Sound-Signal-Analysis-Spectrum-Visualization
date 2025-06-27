# Python for Sound: Signal Analysis & Spectrum Visualization

Welcome! This repository hosts a practical Jupyter Notebook designed to guide you through the fundamentals of sound signal analysis and spectrum visualization using Python. This project is perfect for anyone looking to understand the basics of audio signal processing, from generating fundamental signals to analyzing complex audio files.

## 🌟 Features

-   **Time-Domain Signal Visualization**: Learn to plot waveforms to analyze how a signal's amplitude changes over time.
-   **Fundamental Signal Generation**: Create basic signals like sine and cosine from scratch to understand their frequency and phase properties.
-   **Signal Manipulation**: Perform common operations such as mixing multiple signals and applying rectification.
-   **Frequency Spectrum Analysis**: Utilize the *Fast Fourier Transform* (FFT) to convert signals from the time domain to the frequency domain, allowing us to "see" the frequencies contained within a sound.
-   **Practical Audio File Analysis**: Apply all the learned techniques to analyze a real-world `.wav` audio file—in this case, the sound of a monkey.

## 🚀 Notebook Contents

The `suara.ipynb` notebook walks you through the following key steps:

1.  **Introduction to Signals**: Creating and visualizing simple sine and cosine signals.
2.  **Operations on Signals**: Mixing multiple signals and applying a rectification function.
3.  **Building Complex Waveforms**: Creating more intricate waveforms by adding several harmonics.
4.  **Understanding the Spectrum**: An introduction to the frequency domain concept and how to compute a signal's spectrum using FFT.
5.  **Case Study: Monkey Sound Analysis**:
    * Loading a `.wav` audio file.
    * Visualizing the signal in the time domain.
    * Analyzing the magnitude and phase spectrum to identify the sound's unique characteristics.

## 🛠️ Dependencies

You'll need a few essential Python libraries to run this notebook. Install them all using pip:

```bash
pip install numpy librosa matplotlib
```

-   **NumPy**: For numerical computing.
-   **Librosa**: For audio and music analysis.
-   **Matplotlib**: For creating plots and visualizations.

## 👨‍💻 How to Run

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/Mystery-World3/Python-for-Sound-Signal-Analysis-Spectrum-Visualization.git
    cd Python-for-Sound-Signal-Analysis-Spectrum-Visualization
    ```

2.  **Install Dependencies**:
    For best practice, you can create a `requirements.txt` file with the library names above and install them using:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch Jupyter**:
    Open the `suara.ipynb` notebook using Jupyter Notebook or JupyterLab to get started.
    ```bash
    jupyter notebook sound.ipynb
    ```

*Created by Mystery-World3*
