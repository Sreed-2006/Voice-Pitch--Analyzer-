# Voice Pitch Analyzer & Contour Extractor

A Python application that records live voice audio through a microphone, extracts fundamental pitch frequency ($f_0$) over time using `librosa.pyin`, visualizes the pitch contour, and outputs sampled frequency values at customizable time intervals.

## Features
- Live audio recording via microphone using `sounddevice`
- Fundamental frequency detection using `librosa.pyin`
- Pitch contour visualization with `matplotlib`
- Linear interpolation to sample frequency at custom time steps

## Requirements
To run this project, install the required dependencies:

```bash
pip install librosa matplotlib numpy sounddevice
##output Example
![pitch Contour Graph](Sample_plot)(Table_frequency_vs-time)
