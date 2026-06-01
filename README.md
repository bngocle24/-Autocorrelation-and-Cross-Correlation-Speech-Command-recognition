# 🎤 Speech Command Recognition using Cross-Correlation

A simple speech command recognition system developed using Digital Signal Processing (DSP) techniques. The project recognizes spoken commands by comparing an input speech signal with pre-recorded reference templates using cross-correlation.

---

## Project Title

### Speech Command Recognition using Cross-Correlation

This project implements a template-matching speech recognition system. The user records a voice command through a microphone, and the system compares the recorded signal with stored reference commands.

The command corresponding to the highest correlation score is selected as the recognized output.

---

## Add Shields.io Badges

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NumPy](https://img.shields.io/badge/NumPy-green)
![Librosa](https://img.shields.io/badge/Librosa-orange)
![DSP](https://img.shields.io/badge/Digital%20Signal%20Processing-red)

---

## Project Demo

Add a GIF or video demonstrating:

* Recording a command
* Correlation calculation
* Recognition result

Example:

```html
<img src="demo/demo.gif" width="800">
```

---

## Project Screenshots

### System Architecture

```text
Reference Commands
     │
     ▼
 Load WAV Files
     │
     ▼
 Signal Normalization
     │
     ▼
 Record Test Command
     │
     ▼
 Cross-Correlation
     │
     ▼
 Peak Detection
     │
     ▼
 Command Recognition
```

### Recognition Result

Insert screenshots of:

* Reference signals
* Recorded signal
* Correlation plots
* Recognition output

---

## Features

### Cross-Correlation Based Recognition

Cross-correlation measures the similarity between two signals.

Rxy[m] = Σ x[n]y[n+m]

The highest correlation peak indicates the strongest similarity between the recorded command and a reference template.

### Signal Processing Functions

* Audio recording from microphone
* WAV file loading
* Signal normalization
* Cross-correlation computation
* Peak detection
* Command classification

### Supported Commands

Current implementation:

* "Mở"
* "Tắt"

Additional commands can be added by providing new reference audio files.

---

## Installation Steps

### Clone Repository

```bash
git clone https://github.com/your-username/project-name.git
```

### Navigate to Project Folder

```bash
cd project-name
```

### Install Required Packages

```bash
pip install numpy matplotlib librosa sounddevice wavio
```

### Run Program

```bash
python main.py
```

---

## Contribution Guidelines (Optional)

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Submit a Pull Request

---

## Technologies Used (Optional)

* Python
* NumPy
* Matplotlib
* Librosa
* SoundDevice
* Digital Signal Processing (DSP)

---

## License Information (Optional)

This project is developed for educational and research purposes.

---

## Support Information (Optional)

For questions or suggestions, please create an issue in the repository.

---

## References

* Cross-Correlation
* Autocorrelation
* Speech Signal Processing
* Template Matching Techniques
* Digital Signal Processing (DSP)
