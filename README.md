# Convert Book into AudioBooks

**Convert Book into AudioBooks** is a Python-based tool that converts the content of PDF files into speech using text-to-speech technology. This tool extracts text from PDF files and reads it aloud. It allows users to listen to PDF content like stories, books, or any other document while multitasking or for accessibility purposes.

## Features

- **Extract Text**: Extracts text from all pages of a PDF.
- **Text-to-Speech Conversion**: Converts the extracted text into speech.
- **Customizable Voice Settings**: Allows customization of speech rate, volume, and voice.
- **Save to Audio**: Saves the spoken content as an **MP3** file for later use.

## Requirements

Before running the tool, ensure that you have Python installed and the following dependencies:

- **PyPDF2**: A Python library used to extract text from PDF files.
- **pyttsx3**: A text-to-speech conversion library.

### Install Dependencies

To install the required libraries, use `pip`:

```bash
pip install PyPDF2 pyttsx3
