# VibeVoice Experiments

Audio experiments comparing different configurations of [Microsoft's VibeVoice](https://github.com/microsoft/VibeVoice) text-to-speech model.

## Models Tested

- **Official 1.5B model** - Float32 parameters (original)
- **Custom 1.5B model** - Float16 parameters (unofficial conversion)
- **Custom 7B model** - Float16 parameters (unofficial conversion)

## Audio Samples

The repository includes synthesized speech samples from two voices (Josiah and Tien) across several model configurations, plus reference recordings.

## Demo

Open `index.html` in a web browser to view and listen to all audio samples in a tabular format.

## File Structure

```
├── index.html          # Interactive demo page
├── audio/              # Audio samples
│   ├── Josiah-sample.wav      # Reference
│   ├── Josiah-1.5B-f32.wav    # Official model
│   ├── Josiah-1.5B-f16.wav    # Custom f16 1.5B
│   ├── Josiah-7B-f16.wav      # Custom f16 7B
│   ├── Tien-sample.wav        # Reference
│   ├── Tien-1.5B-f32.wav      # Official model
│   ├── Tien-1.5B-f16.wav      # Custom f16 1.5B
│   └── Tien-7B-f16.wav        # Custom f16 7B
└── README.md
```
