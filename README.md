# 🖼️ Bangla Chitra Net: An Efficient Transformer-Based Architecture for Image Captioning
**Accepted at CVIP 2024**

[![Conference](https://img.shields.io/badge/CVIP-2024-blue.svg)](https://www.cvip2024.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

## 🧠 Abstract

This study presents a novel approach to sequence-to-sequence prediction for the image captioning task. We introduce **Bangla Chitra Net**, a Transformer-based system that receives sequentialized raw images as input. The system incorporates a convolutional neural network (CNN)-based image encoder to extract region-based visual features and a recurrent neural network (RNN)-based caption decoder that utilizes these visual features along with attention mechanisms to generate captions.

While prior work has demonstrated the power of intramodal interactions through co-attention or self-attention, most existing models process sequences sequentially, which can limit efficiency. Recent English-captioning systems have adopted Transformer architectures to address this limitation. However, no such efforts have been directed towards Bengali captions. Our proposed method fills this gap by using a Transformer for efficient Bengali caption generation.

Extensive experiments on the **Flickr8k** and **BAN-Cap** datasets show that Bangla Chitra Net outperforms traditional CNN+Transformer-based methods in both accuracy and fluency of generated captions.

---

## 📂 Repository Structure

