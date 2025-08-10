# ASR Chinese Python Tool

A simple desktop tool for Chinese speech recognition and multi-format subtitle generation using FunASR.

## Features

- Supports Chinese ASR model `paraformer-zh`
- Generates subtitles in SRT, VTT, ASS, and TXT formats
- Simple Tkinter GUI for easy usage
- Audio file format support: WAV, MP3, PCM

## Requirements

- Python 3.7+
- FFmpeg installed and accessible from command line
- Required Python packages:
  - funasr
  - modelscope
  - ffmpeg-python
  - tkinter (usually bundled with Python)

## Installation

```bash
pip install funasr modelscope ffmpeg-python
