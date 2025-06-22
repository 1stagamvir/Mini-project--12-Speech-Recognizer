# Mini project-12 Speech Recognizer 🎤→📝


A robust Python solution for transcribing large audio files by splitting them into manageable chunks based on silence detection.

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
