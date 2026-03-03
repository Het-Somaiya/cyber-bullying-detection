# Cyber Bullying Detection via NLP

A comparative Natural Language Processing framework evaluating Transformer-based architectures against Recurrent Neural Networks to classify harmful content in digital communications.

## 🧠 Model Architecture
- **DistilBERT:** Leveraged a pre-trained Transformer model for high-accuracy contextual understanding.
- **Dual-Layer LSTMs:** Architected a Long Short-Term Memory network with 128 hidden units to capture long-range dependencies in text.
- **Embeddings:** Utilized 50-dimensional word embeddings for dense vector representation of 10,000+ annotated comments.

## 📊 Performance & Optimization
- **Accuracy:** Achieved a **99.5% training accuracy** through rigorous hyperparameter tuning.
- **Early Stopping:** Implemented Keras callbacks to monitor validation loss and prevent overfitting, ensuring model generalizability.
- **Preprocessing:** Custom pipeline for tokenization, lemmatization, and noise removal from raw social media data.

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Keras, TensorFlow, Scikit-learn, Pandas, NumPy
