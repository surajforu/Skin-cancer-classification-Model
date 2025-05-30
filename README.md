 🧪 Skin Cancer Classification with ResNet50
 📄 Project Overview

Developed a deep learning model using ResNet50 to classify seven types of skin cancer from dermatoscopic images in the HAM10000 dataset.

✅ Handled class imbalance with weighted loss functions.
✅ Achieved 84.32% validation accuracy, outperforming initial VGG19 results.
✅ Demonstrates the potential of deep learning models for clinical diagnostic support.

---

🚀 Dataset

* Dataset: [HAM10000](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)
* Images: 10,015 dermatoscopic images
* Classes: Seven skin cancer types

---

⚙️ Model Architecture

* **Base Model**: ResNet50 (pre-trained on ImageNet)
* **Input Size**: 224 x 224
* **Loss Function**: Weighted Cross-Entropy Loss
* **Optimizer**: Adam

---

## 📈 Results

| Model        | Validation Accuracy |
| ------------ | ------------------- |
| VGG19        | 76.5%               |
| ResNet50     | 84.32%              |

---

📦 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/username/skin-cancer-classification.git
cd skin-cancer-classification

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Train the model
python train.py

# Evaluate the model
python evaluate.py
```

---
 💡 Future Work

* Fine-tuning hyperparameters for further performance improvements
* Exploring other architectures (EfficientNet, Vision Transformers)
* Building a web-based demo for clinical usage

-📜 License

MIT License

---
