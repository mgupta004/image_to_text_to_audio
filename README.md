# Image to Text to Audio

This project implements a pipeline that extracts text from an image using Optical Character Recognition (OCR) and then converts the extracted text into speech using text-to-speech (TTS) technology.

> Note: This project was developed as part of undergraduate coursework at university. It is intended solely for learning and academic exploration.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Author](#author)

## Overview

The goal of this project is to enable a seamless transition from visual to auditory content by:
1. Reading text from an input image using OCR.
2. Converting the recognized text into audio using a text-to-speech engine.

This can be useful in applications such as accessibility tools for visually impaired users, language learning aids, and automated reading systems.

## Features

- Image upload and processing
- Text extraction using Tesseract OCR
- Cleaned and formatted text output
- Text-to-speech conversion using pyttsx3
- Audio output of the extracted content

## Technologies Used

- Python 3.x
- Jupyter Notebook
- Tesseract OCR (`pytesseract`)
- Text-to-Speech Engine (`pyttsx3`)
- Image Processing (`PIL`, `cv2`)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/mgupta004/image-to-text-to-audio.git
   cd image-to-text-to-audio
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Make sure Tesseract-OCR is installed on your system:
   - [Tesseract Installation Guide](https://github.com/tesseract-ocr/tesseract)

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

1. Upload an image containing text.
2. The notebook will:
   - Display the image.
   - Extract text using `pytesseract`.
   - Output the recognized text.
   - Convert and play the audio of the text using `pyttsx3`.

## Project Structure

```
Image_to_text_to_audio/
│
├── Image_to_text_to_audio.ipynb  # Main notebook
├── README.md                     # Project documentation

├── Output.mp3                    # Sample audio output
└── Picture1.png                  # Sample input image
```

## License

This project is for educational purposes only and does not carry any formal license. All third-party libraries are used under their respective licenses.

## Author

**Mitali Gupta**  
Undergraduate Student, Thapar Institute of Engineering and Technology  
GitHub: [mgupta004](https://github.com/mgupta004)
