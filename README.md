# 🍜 Vietnamese Food Image Retrieval

This project uses deep learning (EfficientNet) to **extract visual features from Vietnamese food images** and **retrieve visually similar images** based on cosine similarity.

---

## 🚀 Goal

- Apply AI to search for visually similar Vietnamese food dishes.
- Useful for food recognition, recommendation systems, or building smart visual search apps.

---

## 📦 Dataset

- The dataset is hosted on Kaggle:
  👉 [Vietnamese Foods Dataset on Kaggle](https://www.kaggle.com/datasets/quandang/vietnamese-foods)

- It contains various dish categories like *pho*, *bun bo*, *banh mi*, etc.
- **Size:** ~4GB of food images organized by folder.

---

## 🔧 Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/NguyenLeMinh-dev/Recommend_Food
cd Recommend_Food
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Choose how to run
✅ Option 1: Easiest – Run on Kaggle
- Open the notebook on Kaggle Notebooks
- The dataset is already available → no download/setup needed.

✅ Option 2: Google Colab
- Open the notebook in the notebooks/ folder on Colab:
- You can link your Kaggle account and download the dataset using kagglehub or the Kaggle API.

⚠️ Option 3: Run locally (manual setup)
- If you prefer to run the project locally:
- Download the dataset (~4GB) from Kaggle:
👉 https://www.kaggle.com/datasets/quandang/vietnamese-foods
- Unzip the dataset to the following folder:
- data/vietnamese-foods/
- Ensure your folder structure looks like this:
```bash
Recommend_Food/
├── data/
│   └── vietnamese-foods/
│       ├── pho/
│       ├── bun-bo/
│       └── ...
├── notebooks/
│   └── food_retrieval.ipynb
└── ...
```
⚠️ Note: The dataset is ~4GB. If you're low on disk space or RAM, it’s recommended to run on Kaggle or Colab instead.

---
## 🧠 Features
- Feature extraction using EfficientNetB0.

- Cosine similarity for finding similar images.

- Displays the query image and top similar results.

- Easily extendable for APIs or mobile apps.
---

## 📥 Want to use the dataset locally?

- If you don’t want to download it manually, feel free to open an issue.
- I can provide a direct download link or support with kagglehub.
- However, for convenience, I highly recommend using Kaggle or Colab.
---
## 🛠 Requirements
- See requirements.txt.
- Key packages:
```bash
tensorflow

opencv-python

matplotlib

scikit-learn

numpy
```
---

## 🤝 Contributions
Pull requests and ideas are welcome!
You're encouraged to contribute improvements such as:

- Better models

- Web or mobile integration

- Dataset enhancements
---
## 📬 Contact
- 📧 Email: leminhhu.edu@gmail.com 
- 💼 GitHub: @NguyenLeMinh-dev

