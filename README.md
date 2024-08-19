# Text-to-Speech Conversion using gTTS

This project demonstrates how to convert a given text into speech using the Google Text-to-Speech (gTTS) library. 
The resulting speech is saved as an audio file and can be played directly within a Jupyter notebook.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [License](#license)

## Introduction

The project uses the gTTS library to convert a text passage about machine learning into an audio file. The text is converted into speech in English, and the resulting audio file is saved as `audio.mp3`. 
You can listen to the audio directly within the Jupyter notebook.

## Requirements

- Python 
- Jupyter Notebook

### Python Packages

- gTTS
- IPython

## Installation

Install the required Python packages:

    ```bash
    pip install gtts IPython
    ```

## Project Structure

```plaintext
text-to-speech/
│
├── README.md
├── text_to_speech.ipynb  # Jupyter Notebook containing the code
├── audio.mp3             # The output audio file (generated after running the notebook)
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
