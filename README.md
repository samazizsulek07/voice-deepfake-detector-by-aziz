# Voice Deepfake Detector

A Machine Learning project that detects whether a voice recording is real or AI-generated.

## Features

- Live microphone recording
- Deepfake voice detection
- Confidence score
- Real-time analysis
- Modern web interface

## Technologies

- FastAPI
- Python
- Scikit-learn
- Librosa
- JavaScript
- HTML/CSS

## Installation

### Backend

```bash
cd backend
pip install -r requirements.txt
python train.py
uvicorn main:app --reload