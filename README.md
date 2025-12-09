# AI_Bots – COMP‑6321 Applied ML

**Team members**
Mohammed Shurrab (40323793)    Patrick Liam O’Connor (40310129) 
Shariq Anwar (40321507)        Dan Munteanu (40351135)

---

## Repository Overview

### PixelParlance Project: Mitigating Hallucinations in Automatic Image Captioning
a grounded image captioning system built on a modern Vision Transformer (ViT) encoder – Transformer decoder architecture. This repository includes all the required dependencies to run the project. It details the Dataset download and generation of the Dataloaders along with the proposed model and the baseline. 
It contains two files, Final_Project which includes our model and experiments setup.. and Baseline which includes the CNN, attention-based LSTM benchmark along with experimental setup and evaluation.
---

## How to Set Up
Please note that all simulations were run on kaggle so it is best to replicate results in kaggle notebook to take advantage of GPU accelerator

1. Clone the repository:
   ```bash
   git clone https://github.com/shariqanwar20/PixelParlance-Comp6321.git
   cd PixelParlance-Comp6321
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate       # macOS/Linux
   venv\Scripts\activate        # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage Guide

### Proposed Model
- Navigate to `Final_Project.ipynb` to explore dataset loading, model setups, and evaluation.

### Baseline
- Open `Baseline.ipynb` to run the baseline training and visualize results.

  
- The detailed analysis is available in `Project_report.pdf` and `Project_presentation.pptx`.

---

## License

This project is released under the **MIT License**. Please see the `LICENSE` file at the root of the repository.

---

## Contributing & Support

We welcome contributions!
- Fix bugs
- Improve documentation
- Suggest new features

Feel free to open issues or pull requests. Include context, notebook updates, or scripts as needed.

---

## Acknowledgements

- COCO 2017 Dataset
- timm Vision Transformer library
- open_clip
- PyTorch ecosystem
- Kaggle for GPU compute
