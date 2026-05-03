🖼️ Image Caption Generator

A deep learning project that automatically generates natural language captions for images.
Built with a CNN+LSTM merge architecture — EfficientNetB0 extracts visual features,
which are then fed into an LSTM language model to produce descriptive captions.

🔧 Tech Stack
- Python, TensorFlow / Keras
- EfficientNetB0 (ImageNet pretrained, frozen)
- LSTM-based sequence model
- Flickr8k dataset (1000 images)

✨ Features
- Greedy decoding & temperature sampling
- Teacher forcing during training
- Early stopping & learning rate scheduling
- Upload your own image and get a caption instantly

🚀 Run it
Open in Google Colab (GPU recommended) and run all cells top to bottom.
Requires a free Kaggle account to download the dataset.
