# Twitter Platform Sentiment Analysis

## Overview

In the era of digital communication, social media platforms such as Twitter, Facebook, Instagram, or Threads have emerged as prominent channels for individuals to express opinions, share experiences, and engage in public discourse. With millions of tweets generated daily, Twitter represents a vast and dynamic source of data that reflects public sentiment on a wide range of topics, including politics, consumer products, social issues, and global events. However, the unstructured and high-volume nature of these data presents significant challenges for manual analysis and interpretation.

Our project seeks to address the problem of efficiently analyzing public sentiment on Twitter through the application of sentiment analysis, which aims to classify textual data based on emotional tone. The ability to systematically analyze the sentiment on social networks has significant implications in multiple domains. For businesses, it enables the identification of customer satisfaction trends, supports reputation management, and informs product or service improvements. In the political arena, sentiment analysis offers insight into public opinion, facilitating more responsive and strategically informed campaign messaging. In marketing, sentiment analysis helps uncover consumer preferences and enhances the development of targeted advertising strategies, etc.  

Through this project, our goal is to build a robust analytical framework that contributes to data-driven decision-making in both academic research and industry practice.

## Repository Structure

```
.
├── dataset/               # Dataset files and metadata   
│   ├── README.md 
│   ├── train.csv
│   └── test.csv 
├── notebook/               # Jupyter notebooks for models   
│   ├── BERT.ipynb 
│   ├── LSTM.ipynb 
│   ├── SVM.ipynb
│   ├── MultinomialNB.ipynb
│   ├── DistilBERT.ipynb
│   └── RoBERTa.ipynb
├── README.md
├── presentation.pdf       # Project presentation slides
└── final_report.pdf       # Detailed project report
```

## Getting Started

1. Clone this repository.
 ```bash
   git clone https://github.com/tunglambg131003/NLP-Project.git
   cd NLP-Project
 ```
2. Open the Jupyter notebooks in the `notebook/` directory to reproduce the analysis:

- `BERT.ipynb`
- `LSTM.ipynb `
- `SVM.ipynb`
- `MultinomialNB.ipynb`
- `RoBERTa.ipynb`
- `DistilBERT.ipynb`

3. Ensure you have all necessary dependencies installed. A typical setup includes:

- Python 3.11+
- pandas
- transformers
- dataset
- nltk
- numpy
- matplotlib
- plotly
- scikit-learn

# Importance 

All notebooks are designed to be run on **Google Colab** for ease of access and GPU acceleration. Please make sure to:

- **Update file paths** to match your own directory structure. 

- **Provide your Hugging Face access token** if using transformer models that require authentication.

## Acknowledgement

This project is conducted as part of COMP4020 - Natural Language Processing course at our university. We would like to express our heartfelt appreciation to our course instructor and teaching assistants for their guidance, insightful feedback, and continued support throughout the development of this project.

## Authors and Contact Information

- **Nguyen Tung Lam**  
  *Computer Science, VinUniversity*  
  Email: [21lam.nt@vinuni.edu.vn](mailto:21lam.nt@vinuni.edu.vn)

- **Nguyen Duc Trung**  
  *Computer Science, VinUniversity*  
  Email: [22trung.nd@vinuni.edu.vn](mailto:22trung.nd@vinuni.edu.vn)

- **Nguyen Nhat Nam**  
  *Computer Science, VinUniversity*  
  Email: [23nam.nn@vinuni.edu.vn](23nam.nn@vinuni.edu.vn)

Feel free to contact us with any questions, suggestions, or comments related to this project. We welcome any feedback that can help improve this work or contribute to further research in the domain of sentiment analysis.
