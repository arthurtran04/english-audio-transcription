# English Audio Transcription using Whisper model

## Introduction



## Table of Contents

- [Introduction](#introduction)
- [Prerequirements](#prerequirements)
- [Project Structure](#project-structure)
- [Model](#model)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [License](#license)

## Prerequirements

- ![Python 3.9](https://img.shields.io/badge/Python-3.9-blue) or above: [Download here](https://python.org/downloads)

## Project Structure

```
english-audio-transcription/
├── .gitignore
├── app.py
├── requirements.txt
├── LICENSE
└── README.md
```

## Model

- [openai/whisper-small](https://huggingface.co/openai/whisper-small)

## Features

- English Audio Transcription using Whisper model from OpenAI
- Intuitive Gradio UI for easy interaction

## Installation

To install this project, open your Terminal and follow these steps:

1. Clone the repository:

    ```sh
    $ git clone https://github.com/arthurtran04/english-audio-transcription.git
    ```

2. Change the directory to `english-audio-transcription`:

    ```sh
    $ cd "$(find . -type d -name "english-audio-transcription")"
    ```

3. Create a Python virtual environment `.venv` and install the required dependencies:

    ```sh
    $ python3 -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    ```

## Usage

To start the application, run the `app.py` file:

   ```sh
   $ python app.py
   ```
This application will run locally at `http://127.0.0.1:7860`:

<img width="600rem" alt="Webpage" src="https://github.com/user-attachments/assets/c24661d0-d5a2-43b9-9ce0-1bea6a3fd69a"/>

Upload your audio file in the left box and click **Submit** button, the application will generate the transcription in the right box:

<img width="600rem" alt="Example" src="https://github.com/user-attachments/assets/67b1802f-319d-42a5-b1c9-1e5cb0dc4fa8"/>

To stop the application, use `Ctrl + C` in the Terminal

## Demo

My demo on Hugging Face Spaces: [link](https://huggingface.co/spaces/josephtran04/english-audio-transcription)

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
