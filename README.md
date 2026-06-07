# Plant Disease Classification Project

This project explores and benchmarks various Deep Learning architectures to classify plant diseases from leaf images. As part of a 3rd-year academic project, the goal was to develop an efficient and accurate model capable of assisting in early disease diagnosis to help improve agricultural yields.

---

## 📊 Performance Leaderboard

Through systematic evaluation, the models were tested against a standardized dataset. The custom-optimized **ResNet50** architecture emerged as the top performer.

| Model Architecture | Accuracy |
| --- | --- |
| **Custom ResNet50** | **98.82%** |
| Custom EfficientNetB0 | 97.36% |
| Custom VGG16 | 97.30% |
| ResNet50 (Baseline) | 96.68% |
| Sequential (CNN) | 96.43% |
| EfficientNetB0 (Baseline) | 94.63% |
| Custom MobileNetV2 | 79.21% |

---

## 🚀 Key Features

* **Comparative Analysis:** Performance benchmarking of standard architectures against custom-tuned variants.
* **Optimization:** Focused on fine-tuning hyperparameters and architecture depth to maximize diagnostic accuracy.
* **Dataset Handling:** Implemented preprocessing and augmentation pipelines to improve model robustness and generalization.

## 🛠 Tech Stack

* **Language:** Python
* **Frameworks:** TensorFlow / Keras
* **Tools:** Jupyter Notebooks, Matplotlib (for visualization)

## 📂 Project Structure

* `Proposed_Resnet50_&Seq_test3_Train_plant_disease.ipynb`: Contains the primary implementation, training pipelines, and evaluation metrics for the ResNet50 and Sequential models.
* `models/`: Directory containing serialized weights for the trained architectures.
* `data/`: Configuration for dataset loaders and preprocessing scripts.

---

## 💡 How to Run

1. **Clone the repository:**
```bash
git clone <repository-url>

```


2. **Install dependencies:**
Ensure you have the required libraries installed:
```bash
pip install tensorflow pandas matplotlib

```


3. **Execute the Notebook:**
Open `Proposed_Resnet50_&Seq_test3_Train_plant_disease.ipynb` in Jupyter Lab or Google Colab to view the training process and evaluation results.

---

*Developed as a 3rd-year undergraduate project, focusing on applying deep learning techniques to real-world agricultural challenges.*
