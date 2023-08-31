# AdaptiveHuffmanWithML
An Adaptive Huffman Text Compressor integrated with a simple machine learning model for character prediction
# Adaptive Huffman Text Compressor with ML

## Overview
This project integrates an Adaptive Huffman Text Compressor with a simple machine learning model for character prediction.

## Features
- Adaptive Huffman Coding for text compression
- GPU-Accelerated frequency count using CuPy
- Asynchronous batch processing with asyncio
- Simple character prediction using scikit-learn's MultinomialNB

## Requirements
- Python 3.x
- CuPy
- scikit-learn
- asyncio

## Installation
```bash
pip install cupy scikit-learn
# Import the AdaptiveHuffmanCompressor class
from adaptive_huffman import AdaptiveHuffmanCompressor

# Initialize and run the compressor
compressor = AdaptiveHuffmanCompressor()
compressed_text = compressor.run("your_text_here")
