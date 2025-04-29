# Voice Activity Detection (VAD) with Energy Thresholding and Signal Framing

This notebook implements a simple yet effective Voice Activity Detection (VAD) system using basic signal processing techniques. It processes audio files to identify segments containing speech by applying energy thresholding on framed signals. The notebook includes functionalities to:
- Load and preprocess .wav audio files
- Segment audio using short-time framing
- Compute energy levels for each frame
- Identify speech frames based on energy thresholds
- Visualize detected speech segments against the original waveform
