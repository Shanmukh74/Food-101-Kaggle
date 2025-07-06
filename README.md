# Food-101-Kaggle
ProdigyInfotech Task 5

📁 Food-101 Dataset (dansbecker/food-101)
Description
Food-101 is a large-scale, real-world dataset consisting of 101 food categories, with 101,000 images total—750 training and 250 test images per class. The test labels have been manually cleaned, while the training set contains some noise 
huggingface.co
+2
kaggle.com
+2
github.com
+2
kaggle.com
+6
paperswithcode.com
+6
kaggle.com
+6
.

Source
Originally introduced in “Food-101 – Mining Discriminative Components with Random Forests” by Lukas Bossard et al. 
kaggle.com
+2
kaggle.com
+2
paperswithcode.com
+2
.

Directory Structure

bash
Copy
Edit
food-101/
├── images/      # Raw images, organized by category
└── meta/
    ├── train.txt
    └── test.txt
Usage

Download and unzip the dataset.

Each category folder under images/ contains the respective food images.

meta/train.txt and meta/test.txt list the image IDs for training and testing.

Applications

Fine-grained image classification

Learning with noisy labels

Zero-shot and few-shot learning 
github.com
paperswithcode.com
+1
github.com
+1

🖊️ Fathima Lamya – CIFAR‑10 Object Recognition Notebook
Link: fathimalamya/fathima-lamya-mid

Overview
This Kaggle Notebook focuses on image recognition using the CIFAR-10 dataset, experimenting with various ML models to perform object classification 
kaggle.com
+3
kaggle.com
+3
github.com
+3
.

Key Features

Load and preprocess CIFAR‑10 images.

Train and validate simple architectures (e.g., CNNs).

Analyze model performance via metrics and sample predictions.

(Optional) Hyperparameter tuning and augmentation techniques.

Usage

Open and run the notebook on Kaggle (or locally via Jupyter).

Steps typically include: data import → preprocessing → model definition → training → evaluation → visualization.

🧩 Combined README for the GitHub Repository
markdown
Copy
Edit
# Food‑101 + CIFAR‑10 Image Recognition

## 📚 Datasets

### Food‑101
- **Source:** dansbecker/Food‑101 on Kaggle  
- **Details:** 101 food categories, 101K images (750 train / 250 test per class) :contentReference[oaicite:20]{index=20}  
- **Structure:**
food-101/
├── images/
└── meta/
├── train.txt
└── test.txt

markdown
Copy
Edit
- **Usage:** For fine‑grained food image classification tasks.

### CIFAR‑10 Notebook by Fathima Lamya
- A Kaggle Notebook exploring CNN-based classification on CIFAR‑10 :contentReference[oaicite:21]{index=21}.  
- Includes data loading, model training, evaluation, and visualization.

---

## 🛠️ Setup & Usage

### Food‑101
1. Download dataset from Kaggle.
2. Unzip into `food-101/` directory.
3. Use training/testing splits from `meta/` for model development.

### CIFAR‑10 Notebook
- Launch the Kaggle notebook or run locally:
```bash
jupyter notebook Fathima‑Lamya‑MID.ipynb
📈 Projects & Experiments
Food-101: Train/test fine-grained classifiers, implement noise handling, explore data splits.

CIFAR-10 Notebook: Experiment with simple CNN architectures, track performance and visualize results.

🧩 Contributions
Any improvements to preprocessing, augmentation, model architecture, or results welcome via PR.

📖 References
Food‑101 dataset and original paper 
github.com
+9
kaggle.com
+9
github.com
+9
kaggle.com
+9
paperswithcode.com
+9
github.com
+9
kaggle.com

Fathima Lamya CIFAR‑10 classification notebook 
kaggle.com
+1
uk.linkedin.com
+1

yaml
Copy
Edit

---

Let me know if you’d like to adjust the tone, add badges (e.g. dataset download link), or include specific usage scripts and requirements!
::contentReference[oaicite:29]{index=29}











Sources

Ask ChatGPT
