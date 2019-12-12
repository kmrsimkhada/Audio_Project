# Separation of drums from music signals

This project was a compulsary part of the course "Introduction to Audio Processing".  
### Requirements:

Separation of harmonic and percussive components from music spectrogram (time-frequency domain)

• Anisotropy: dependence on direction

• Temporal continuity of harmonic sounds

• Temporal localization of percussive sounds (continuity along frequency)

• Iterative search for such spectrograms that maximize the anisotropy (continuity over time vs. over frequency)

• Together, the two spectrograms (harmonic / percussive) equal the original spectrogram: Hh,i + Ph,i = Wh,i


### Libraries used: 

• Librosa

• Matplotlib for plotting the spectrogram

• Sounddevice for listening the signals.

• Numpy

• scipy.io wavfile to read the audio file

### Implementation:

Started by writing a function to plot spectrogram. Then, audio signal was taken, applied the windowing and with the 50% overlap and calculated and plotted the spectrogram. After that, a for loop was setup to update Hh,i + Ph,i = Wh,i. Then, plotted the iteratively-updated components H(h,i) and P(h,i) which is followed by binarizing. Then, ISTFT was applied to get h(t) and p(t). Finally, saved the seperated components h(t) and p(t).


### Result:

• Two different seperated audio signals harmonic one and percussive one was generated. 
