# Separation of drums from music signals

This project was a compulsary part of the course "introduction to Audio Processing".  
### Requirements:

Separation of harmonic and percussive components from music spectrogram (time-frequency domain)

• Anisotropy: dependence on direction

• Temporal continuity of harmonic sounds

• Temporal localization of percussive sounds (continuity along frequency)

Iterative search for such spectrograms that maximize the anisotropy (continuity

• over time vs. over frequency)

• Together, the two spectrograms (harmonic / percussive) equal the original spectrogram: Hh,i + Ph,i = Wh,i


Libraries used: 

• Librosa

• Matplotlib for plotting the spectrogram

• Sounddevice for listening the seperated signals.

• Numpy


Result:

• Two different seperated audio signals harmonic one and percussive one was generated. 



