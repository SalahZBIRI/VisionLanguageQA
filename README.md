# VisionLanguageQA

# Visual Question Answering (VQA) Model

This project implements a Visual Question Answering (VQA) model that combines advanced computer vision and natural language processing techniques to answer questions based on images.

## Model Architecture

The model is composed of the following integrated sub-modules:

1. **Visual Feature Extractor**: Uses a pre-trained ResNet50 to extract visual features from images.
2. **Question Encoder**: Encodes textual questions using a pre-trained BERT model.
3. **Cross-Attention Mechanism**: Merges visual features and text embeddings through a cross-attention mechanism.
4. **Answer Generator**: Generates textual answers using BART for conditional text generation.

## Installation

### Prerequisites

- Python 3.8 or later
- GPU with CUDA installed (for faster computation)
- PyTorch
- Transformers library (Hugging Face)


