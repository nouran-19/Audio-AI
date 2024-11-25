# Custom Mel Spectrogram Implementation

A Python implementation of mel spectrogram generation from scratch, with comparisons against librosa's implementation. Inspiration: [Mel Spectrograms Explained Easily - Valerio Velardo - The Sound of AI](https://www.youtube.com/watch?v=9GHCiiDLHQ4)

## Requirements

```
librosa
numpy
matplotlib
soundfile
scipy
```

## Features

- Raw waveform visualization
- STFT computation and visualization
- Custom mel filterbank implementation
- Mel spectrogram generation
- Side-by-side comparison with librosa's implementation
- Analysis of differences between implementations



## Implementation Details

- Uses librosa's STFT implementation for consistency
- Implements mel scale conversion and filterbank generation from scratch
- Matches librosa's default parameters for direct comparison
- Provides visualization tools for analysis

## Visualization Components

1. Raw audio waveform
2. STFT magnitude spectrogram
3. Mel filterbank visualization
4. Custom mel spectrogram
5. Librosa mel spectrogram
6. Difference analysis between implementations

## Notes

- Audio is padded using librosa's padding behavior
- Uses Hann window for STFT computation
- Matches librosa's mel frequency conversion