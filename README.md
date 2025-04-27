# 🛒 AI-DRIVEN TEXT AND IMAGE-BASED CLASSIFICATION OF DIGITAL CONTENT IN E-COMMERCE

This project presents an end-to-end machine learning solution for classifying e-commerce products using both **textual descriptions** and **images**. Leveraging **NLP** and **Computer Vision**, we enhance product categorization through a multimodal pipeline built on modern ML techniques.

---

## 📁 Repository Structure

```
Topics_Project/
│
├── Source_Code/
│   ├── PART_01_FINAL_TEXT_edited.ipynb         # Text classification using TF-IDF, Word2Vec, BERT
│   ├── PART_02_FINAL_IMAGE_edited.ipynb        # Image classification using CNN, ResNet, EfficientNet
│
├── Report/
│   ├── Final_Project_Report.pdf                # Complete documentation (15 pages)
│
├── Dataset/ (not uploaded due to size limits)
│   └── Source: Flipkart Products Dataset on Kaggle
│       https://www.kaggle.com/datasets/PromptCloudHQ/flipkart-products 
│
├── README.md
└── .gitignore
```

---

## How to Use This Project

### Prerequisites

- Python 3.8+
- Jupyter Notebook / Google Colab
- Libraries: `numpy`, `pandas`, `scikit-learn`, `tensorflow`, `keras`, `nltk`, `transformers`, `matplotlib`, `seaborn`

Install required packages:
```bash
pip install -r requirements.txt
```

### Running the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/Nagamedha/Topics_Project.git
   cd Topics_Project/Source_Code
   ```

2. Open the notebooks in:
   - **Jupyter Lab** (locally)  
   - **Google Colab** (recommended for BERT + CNNs)

   - `PART_01_FINAL_TEXT_edited.ipynb`: Executes text classification.
   - `PART_2_image_classification.ipynb`: Executes image classification.

> 🔗 To view the **executed notebooks with output**, use our [Google Drive folder](https://drive.google.com/drive/folders/1sU9TBAvQ7TWwWebxWyefq0wtr0AEc9-S?usp=sharing).

---

## Project Summary

- **Text Embeddings**: TF-IDF, Word2Vec, BERT
- **Image Models**: CNN, ResNet, EfficientNet
- **Multimodal Integration**: Dense neural networks
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score

---

## Future Scope

- Extend to **multi-facet classification** (e.g., brand, usage, material)
- Adapt for **real-time classification** at larger scale
- Explore **semi-supervised learning** for sparse labels

---

## ⚠Known Limitations

- Dataset size constrained to ~1000 samples for experimentation
- GitHub excludes heavy datasets and model binaries
- Full notebook outputs are available via Drive only

---

## Conclusion

This project demonstrates how multimodal ML approaches can automate product categorization and improve recommendation and search systems in e-commerce environments. The model pipeline is modular, scalable, and ready to be extended.

Repository Links:
o GitHub Repository: Source code, setup instructions, Documentation
o https://github.com/Nagamedha/Topics_Project
o Google Drive: Executed notebook files for Outputs and Results Visualization
o https://drive.google.com/drive/folders/1sU9TBAvQ7TWwWebxWyefq0wtr0AEc9-S?usp=drive_link
