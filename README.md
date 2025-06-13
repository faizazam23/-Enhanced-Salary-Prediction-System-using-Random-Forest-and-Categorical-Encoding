# English to Urdu Machine Translation using MarianMT

This project is a simple yet effective Machine Translation system that converts English sentences to Urdu using the **MarianMT Transformer model** from the Hugging Face Transformers library.

##  Features

- Translates English text to Urdu using `Helsinki-NLP/opus-mt-en-ur`
- Clean and responsive GUI built with `Tkinter`
- Pretrained MarianMT model with high-quality translation output
- Easy-to-run Python script with minimal setup

##  Model Used

- **Model Name:** Helsinki-NLP/opus-mt-en-ur
- **Architecture:** MarianMT (Transformer-based encoder-decoder)
- **Source:** Hugging Face Transformers library

##  How It Works

1. User enters English text in the input box.
2. The system tokenizes the text and feeds it into the MarianMT model.
3. The model returns translated Urdu text.
4. The output is displayed in a dedicated Urdu output box.

##  Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/english-to-urdu-translation.git
    cd english-to-urdu-translation
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the app:
    ```bash
    python app.py
    ```

##  GUI Preview

- Simple interface with two text boxes (English input and Urdu output)
- One-click translation using the "Translate" button

##  Project Structure

```
├── app.py                  # Main application file with GUI
├── requirements.txt        # Required Python packages
├── README.md               # Project overview and instructions
```

##  Requirements

- Python 3.7+
- `transformers`
- `torch`
- `sentencepiece`
- `tkinter` (usually comes pre-installed with Python)

##  Example

**Input:** `Hello, how are you?`  
**Output:** `ہیلو، آپ کیسے ہیں؟`

##  References

- Hugging Face MarianMT Documentation: https://huggingface.co/docs/transformers/model_doc/marian
- Helsinki-NLP MarianMT Models: https://huggingface.co/Helsinki-NLP

---

###  Author

Faiz Azam - faiyz.azam@gmail.com 
Bachelors in Artificial Intelligence | NLP Project 2025  
Sindh Madressatul Islam University (SMIU)
