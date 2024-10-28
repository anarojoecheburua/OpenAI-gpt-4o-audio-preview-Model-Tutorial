# 🎧 OpenAI gpt-4o-audio-preview Model Tutorial

## 🌟 Overview

This repository provides a hands-on tutorial demonstrating how to use OpenAI’s `gpt-4o-audio-preview` model using LangChain. It covers everything from setting up your environment to working with audio inputs and outputs, including advanced use cases like tool calling and task chaining.

You’ll find practical examples for:
- 📝 **Audio transcription:** Upload audio files and transcribe them using OpenAI’s `gpt-4o-audio-preview` model.
- 🔊 **Audio generation:** Generate spoken responses based on text inputs.
- 🛠️ **Advanced tool binding:** Bind external tools, like a weather-fetching function, and integrate them into your workflow.
- 🔗 **Task chaining:** Create multi-step workflows that combine tasks, such as transcription followed by tool usage.

## ✨ Features
- 📝 **Audio transcription**: Process audio files (e.g., `.wav`) and generate text-based transcriptions.
- 🔊 **Audio generation**: Generate audio responses in formats like `.wav`, with customisable voice options.
- 🛠️ **Tool binding**: Integrate external tools to extend the model’s functionality (e.g., fetching weather data).
- 🔗 **Task chaining**: Automate workflows by chaining multiple tasks, combining audio and tool-based functionality.

## 📂 Project Structure

```
├── OpenAI_gpt4o_audio_tutorial.ipynb    # Jupyter Notebook with the full tutorial
├── README.md                            # Project description and setup guide
├── requirements.txt                     # Project dependecies
```

## ⚙️ Prerequisites

To run this project, you will need the following:
- 🐍 Python 3.6+
- 🔑 OpenAI API key (You can sign up at [OpenAI](https://platform.openai.com/))
- 📦 Install the required packages using the provided instructions.

## 🛠️ Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/anarojoecheburua/OpenAI-gpt-4o-audio-preview-Model-Tutorial.git
   cd your-repo-name
   ```

2. **Set up a virtual environment:**

   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows use: .\env\Scripts\activate
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set your OpenAI API Key:**

   You can set your OpenAI API key as an environment variable:

   ```bash
   export OPENAI_API_KEY='your-api-key-here'  # On Windows use: set OPENAI_API_KEY='your-api-key-here'
   ```

   Alternatively, store your API key in a `.env` file and load it in the script.

5. **Run the Jupyter Notebook:**

   ```bash
   jupyter notebook OpenAI_gpt4o_audio_tutorial.ipynb
   ```

## 🚀 Usage

- 📝 **Audio Transcription:** Encode your audio files, pass them to the model, and get a transcription as output.
- 🔊 **Audio Generation:** Generate spoken responses by configuring the model with audio output capabilities.
- 🔗 **Advanced Workflow:** Chain tasks together, combining transcription and tool usage in a seamless flow.

## ☕ Support My Work
If you found this project helpful and want to support my work, feel free to buy me a coffee! Your support helps me continue creating more tutorials, projects, and open-source contributions like this one. Every coffee is greatly appreciated! 🙌
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support%20Me-orange?logo=buy-me-a-coffee)](https://www.buymeacoffee.com/anarojoecheburua)

