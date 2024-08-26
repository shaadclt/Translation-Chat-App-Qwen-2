# Translation and Chat App using Qwen 2 and Gradio
This project is a Jupyter Notebook-based application that allows users to translate text into different languages (English, Chinese, and Japanese) or chat with an AI model. The notebook utilizes the Qwen/Qwen2-1.5B-Instruct language model for natural language processing tasks and the gTTS library for text-to-speech conversion.

## Features
- **Translate Text**: Translate input text into English, Chinese, or Japanese.
- **Chat Functionality**: Chat with the AI model by selecting the "Chat" option.
- **Text-to-Speech**: Convert the translated or generated text into speech and download the audio file.

## Requirements
Ensure you have the following Python packages installed in your environment:

```bash
pip install accelerate gTTS gradio transformers torch
```

## How to Use
1. Clone the Repository:

```bash
git clone https://github.com/shaadclt/Translation-Chat-App-Qwen-2.git
cd Translation-Chat-App-Qwen-2
```

2. Open the Jupyter Notebook:

- Launch Jupyter Notebook in your working directory:
```bash
jupyter notebook
```
- Open translation_chat_app.ipynb in the Jupyter interface.

3. Run the Notebook:
- Execute each cell in the notebook sequentially.
- Input your text, select the desired action (Translate to English, Translate to Chinese, Translate to Japanese, or Chat), and get the output text along with an audio file.

## License
This project is licensed under the [MIT License](LICENSE.txt). See the LICENSE file for more details.

## Acknowledgements
- **Qwen/Qwen2-1.5B-Instruct** model by Hugging Face.
- **gTTS**: Python library for Google Translate's text-to-speech API.
- **Gradio**: Interface library for machine learning models.
  
## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any improvements or feature requests.

