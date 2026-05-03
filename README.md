# 🧠 Image Caption Generator (CNN + LSTM)

This project implements an **Image Caption Generator** that automatically generates textual descriptions for images using deep learning techniques. It combines computer vision and natural language processing to understand image content and convert it into meaningful sentences.

---

## 🚀 Overview

The model uses a pretrained convolutional neural network like ResNet50 for extracting image features, and a recurrent neural network with LSTM layers to generate captions word-by-word.

---

## ⚙️ Architecture

1. **Feature Extraction (CNN)**

   * Extracts high-level image features using ResNet50

2. **Sequence Model (LSTM)**

   * Generates captions based on image features and previous words

3. **Text Processing**

   * Tokenization and padding of captions

4. **Decoder**

   * Combines image features + text input to predict next word

---

## 🗂 Dataset

This project uses publicly available datasets:

* Flickr8k
* Flickr30k
* MSCOCO

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## ▶️ How to Run

```bash
# Clone repo
git clone https://github.com/your-username/image-caption-generator.git

# Install dependencies
pip install -r requirements.txt

# Run notebook / script
```

Or simply run in Google Colab.

---

## 📊 Sample Output

Input Image → Output Caption

"A dog is running in the grass"

---

## ✨ Features

* End-to-end caption generation
* Pretrained CNN feature extraction
* LSTM-based sequence modeling
* Easy to run on Google Colab

---

## 🚀 Future Improvements

* Attention mechanism
* Beam search decoding
* Transformer-based models
* BLEU score evaluation

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve the project.

---

## 📜 License

This project is open-source under the MIT License.
