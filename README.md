# Mini project-12 Speech Recognizer
# Audio Chunk Transcriber 🎤→📝

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)

A robust Python solution for transcribing large audio files by splitting them into manageable chunks based on silence detection.

## Table of Contents
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Configuration](#%EF%B8%8F-configuration)
- [Project Structure](#-project-structure)
- [Examples](#-examples)
- [Limitations](#-limitations)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

- **Intelligent Chunking**: Splits audio at natural pauses for better accuracy
- **Multi-Source Input**: Works with WAV files (convert other formats using included utility)
- **Cloud & Offline Options**: Supports Google Speech Recognition (online) and PocketSphinx (offline)
- **Format Preservation**: Maintains proper sentence structure and punctuation
- **Batch Processing**: Handle multiple files sequentially
- **Progress Tracking**: Real-time progress indicators

## 🛠 Installation

### Prerequisites

- Python 3.7+
- ffmpeg

```bash
# Clone the repository
git clone https://github.com/yourusername/audio-chunk-transcriber.git
cd audio-chunk-transcriber

# Install dependencies
pip install -r requirements.txt

# Install ffmpeg (Ubuntu/Debian)
sudo apt install ffmpeg
