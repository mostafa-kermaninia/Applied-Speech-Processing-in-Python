
# 🎙️ Applied Speech Processing & Audio AI in Python

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Machine_Learning-f7931e?style=for-the-badge&logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Welcome to the **Applied Speech Processing & Audio AI** repository. This project-based curriculum is a comprehensive roadmap that bridges the gap between low-level Digital Signal Processing (DSP) and high-level Artificial Intelligence. 

Starting from the raw physics of sound waves, this repository guides you through extracting meaningful audio features, building machine learning classifiers, and ultimately deploying advanced modern architectures like **Whisper (ASR)**, **Zero-shot TTS**, and real-time **Voice Assistants**.

---

## 🗺️ Course Roadmap & Curriculum

### 🎛️ Phase 1: Signals, Mathematics, & Tools
* **Lecture 1: Dissecting Sound in Python**
  * *Concepts:* Physics of sound, Analog-to-Digital Conversion (ADC), Sample Rate, Bit Depth, and the Nyquist Theorem.
  * *Lab:* Loading audio and plotting waveforms using `librosa` and `matplotlib`.
* **Lecture 2: Decoding Sound with the Fourier Transform**
  * *Concepts:* Time vs. Frequency domains, the math behind the Discrete Fourier Transform (DFT).
  * *Lab:* Utilizing `np.fft` to extract fundamental frequencies and comparing vowels vs. consonants.
* **Lecture 3: Seeing Sound with Spectrograms**
  * *Concepts:* Overcoming Fourier uncertainty, Short-Time Fourier Transform (STFT), and Windowing functions (Hanning/Hamming).
  * *Lab:* Visualizing full audio signals over time and frequency.
* **Lecture 4: The Audio Fingerprint (MFCC)**
  * *Concepts:* The human auditory system, the Mel Scale, and Cepstral analysis.
  * *Lab:* Extracting the 13 Mel-Frequency Cepstral Coefficients (MFCCs) and visualizing them as heatmaps.

### 🤖 Phase 2: Machine Learning on Audio
* **Lecture 5: Advanced Feature Extraction for ML**
  * *Concepts:* Zero-Crossing Rate (ZCR) and Spectral Centroid.
  * *Lab:* Building structured `pandas` DataFrames to feed audio features into ML pipelines.
* **Lecture 6: Project 1 (Part A) - The World of Emotions**
  * *Concepts:* Introduction to the RAVDESS dataset.
  * *Lab:* Batch processing 100+ audio files, MFCC extraction loop, data normalization, and train-test splitting.
* **Lecture 7: Project 1 (Part B) - Voice Lie Detector**
  * *Concepts:* Classical ML algorithms for audio classification.
  * *Lab:* Implementing Random Forest and SVM via `scikit-learn`, evaluating accuracy matrices, and running a live microphone test to detect emotion/stress.

### 🧠 Phase 3: Modern AI Systems & Applications
* **Lecture 8: Project 2 - Wake Word Detection**
  * *Concepts:* Streaming vs. Static audio processing.
  * *Lab:* Using `pyaudio` for live audio chunking and implementing a keyword trigger system (e.g., "Hey System").
* **Lecture 9: Project 3 - Offline Smart Typist (Speech-to-Text)**
  * *Concepts:* The evolution of ASR from HMMs to Transformers.
  * *Lab:* Setting up **OpenAI Whisper** to achieve highly accurate English/Persian podcast transcriptions.
* **Lecture 10: Project 4 - Speaking AI (Text-to-Speech)**
  * *Concepts:* Online vs. Offline TTS engines and modern TTS architectures (e.g., VITS).
  * *Lab:* Implementing rapid online speech with `gTTS` and offline voices with `pyttsx3`.

### 🌐 Phase 4: Advanced Processing & Deep Learning
* **Lecture 11: Project 5 - Biometric Authentication & Speaker ID**
  * *Concepts:* Speaker Embeddings (d-vector/x-vector) and Cosine Similarity math.
  * *Lab:* Utilizing `pyannote.audio` to build a system that verifies *who* is speaking.
* **Lecture 12: Project 6 - Smart Noise Reduction**
  * *Concepts:* DSP Low-pass/High-pass filters and Spectral Gating.
  * *Lab:* Magically cleaning background noise (e.g., hairdryer sounds) from audio files using `noisereduce` without degrading vocal quality.
* **Lecture 13: Project 7 - Voice Cloning with Deep Learning**
  * *Concepts:* Zero-shot TTS algorithms.
  * *Lab:* Deploying the **XTTS** model on Google Colab to clone a human voice using just a 3-second audio sample.
* **Lecture 14: Final Project - Building the "Jarvis" Voice Assistant**
  * *Concepts:* System architecture integration (Microphone $\rightarrow$ Whisper $\rightarrow$ LLM $\rightarrow$ TTS).
  * *Lab:* Assembling previous modules into a single, comprehensive Python script to create a fully conversational AI assistant. Discussion on freelancing and international market opportunities.

---

## ⚙️ Getting Started

### Prerequisites
Make sure you have Python 3.8+ installed. It is highly recommended to use a virtual environment (`venv` or `conda`).

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/Applied-Speech-Processing-in-Python.git](https://github.com/your-username/Applied-Speech-Processing-in-Python.git)
   cd Applied-Speech-Processing-in-Python

```

2. Install the required dependencies:
```bash
pip install -r requirements.txt

```


*(Note: For Deep Learning models like Whisper and XTTS, you may need to install PyTorch separately based on your CUDA configuration).*
3. Launch Jupyter Notebook:
```bash
jupyter notebook

```



---

## 👨‍💻 About the Author

**Mostafa Kermani Nia** | *Full-Stack Engineer & Computer Engineering Mindset*

I am a Full-Stack Engineer and the Chief Teaching Assistant for Artificial Intelligence at the University of Tehran. My technical philosophy revolves around bridging the gap between low-level systems programming (operating systems, memory management) and high-level Machine Learning architectures.

My ongoing research and professional work focus heavily on Systems for ML, efficient model architectures, and advanced computer vision/audio analysis, specifically concerning noise reduction and speaker identification algorithms.

If you have questions regarding the underlying mathematics, memory-efficient implementations, or scaling these audio models, feel free to open an issue or connect!

---

## 📜 License

This repository is licensed under the MIT License. See the [LICENSE](https://www.google.com/search?q=LICENSE) file for more information.

```
