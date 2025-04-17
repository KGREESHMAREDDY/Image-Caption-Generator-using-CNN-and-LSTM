🧠📸 Image Captioning Using CNN and LSTM

Caption generation is a challenging artificial intelligence task where a textual description is generated for a given photograph.

It combines techniques from:

Computer Vision – to understand the content of the image
Natural Language Processing (NLP) – to generate a coherent and meaningful sentence based on that understanding
Recent advances in deep learning have enabled end-to-end models that generate captions without the need for complex pipelines or extensive manual feature engineering. These models use CNNs to extract features from the image and LSTMs to generate the text sequence, achieving state-of-the-art results.

🗂️ Dataset

Dataset Used: Flickr 8k Dataset
Captions: Flickr8k Text Descriptions

🧠 Model Architecture

CNN: Pretrained CNN (e.g., InceptionV3 / VGG16) to extract image features
LSTM: Processes the sequence of words conditioned on image features
Embedding Layer: Converts input words to dense vector representations
Dense Layer: Outputs probability distribution over the vocabulary

