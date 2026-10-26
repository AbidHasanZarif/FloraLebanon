# FloraLebanon 🌿

Fine-grained plant species classification for Mediterranean ecosystems using Vision Transformers (ViT).

## What it does
Tackles the challenge of identifying closely related plant species in field-collected data where natural class imbalance and subtle visual differences make classification difficult. Built around botanical imagery from the Shouf Biosphere Reserve.

## Key Highlights
* **ViT Backbone:** Leverages `ViT-B/16` (pre-trained on ImageNet) to capture global context and fine-grained botanical features.
* **Custom Attention (CBAM):** Integrates Convolutional Block Attention Modules to sharpen spatial and channel feature refinement.
* **Focal Loss:** Combats severe class imbalance and long-tail distributions common in ecological datasets.
* **Domain Augmentations:** Uses targeted augmentations to prevent overfitting on limited field imagery.

## Quick Start

1. **Clone and install dependencies:**
   ```bash
   git clone [https://github.com/your-username/FloraLebanon.git](https://github.com/your-username/FloraLebanon.git)
   cd FloraLebanon
   pip install -r requirements.txt
