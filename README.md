# Indic TTS Models

## Overview
This repository provides an overview and implementation details of various Indic Text-to-Speech (TTS) models. These models support multiple Indian languages and generate natural-sounding speech from text input. The repository includes Colab links for easy access and testing.

## Available Models

### 1. ai4bharat/indic-parler-tts
- **Size**: 3.8 GB
- **Supported Languages**: 20 Indic languages
- **Inputs**: Text, Voice description
- **Output**: Audio
- **Output**: Audio <audio controls src="./Samples/indic_tts_out.wav" title="Title"></audio>
- **Results**:
  - ✅ Very natural and clear audio
  - ✅ Good accent
  - ❌ Large size
  - ❌ Some inconsistencies
- **License**: Apache 2.0
- **Colab Link**: [Try Here](https://colab.research.google.com/drive/1gNbY04rMS8sz7nfneQTjpucPFoRbFBXm?usp=sharing)

---

### 2. facebook/mms-tts-hin / facebook/mms-tts-guj
- **Size**: 150-160 MB
- **Supported Languages**: Hindi (Separate models for other languages)
- **Inputs**: Text
- **Output**: Audio
- **Results**:
  - ✅ Natural and clear audio
  - ✅ Small model size
  - ❌ Requires switching models for different languages
  - ❌ Some voice inconsistencies
- **License**: CC-BY-NC 4.0
- **Colab Link**: [Try Here](https://colab.research.google.com/drive/1ldGZS8WMReaXntyZ5HUREu1mN1TRhNrZ?usp=sharing)
- **Other Languages**: [Find More Models](https://huggingface.co/models?sort=trending&search=facebook%2Fmms-tts)

---

### 3. ai4bharat/vits_rasa_13
- **Size**: 170 MB
- **Supported Languages**:
  - Assamese, Bengali, Bodo, Dogri, Kannada, Maithili, Malayalam, Marathi, Nepali, Punjabi, Sanskrit, Tamil, Telugu
- **Inputs**: Text
- **Output**: Audio
- **Results**:
  - ✅ Clear audio
  - ✅ Mixed accent support
  - ❌ Slight tone inconsistencies
- **License**: Apache 2.0
- **Colab Link**: [Try Here](https://colab.research.google.com/drive/1E3v_6UsLyCbPEPV5Wko2tkjo1_5OkjOt?usp=sharing)

---

## How to Use
1. Open the Colab link for the desired model.
2. Run the provided cells to set up the environment.
3. Input the desired text (and voice description, if applicable).
4. Generate and listen to the audio output.

## License
- **ai4bharat models**: Apache 2.0 (Permissive use)
- **Facebook MMS-TTS models**: CC-BY-NC 4.0 (Non-commercial use only)

## Contributions
If you’d like to contribute, feel free to submit pull requests or report issues.

## Acknowledgments
Special thanks to AI4Bharat and Facebook for providing open-source Indic TTS models for research and development.

