# Neural Networks & Deep Learning

Coursework from **TC2035 – Redes Neuronales** (Tecnológico de Monterrey): a progression from a single perceptron to modern deep architectures (CNNs and a **Vision Transformer**), plus competitive / unsupervised learning.

## Repository structure
| Folder | Contents |
|--------|----------|
| `01-fundamentals/` | Single **perceptron**, a perceptron cat-classifier, and a **simple neural network** (MLP) built from the ground up. |
| `02-supervised-learning/` | Supervised **classification** and **regression** with neural networks — training loops and evaluation. |
| `03-competitive-learning/` | **Self-Organizing Maps (SOM)** and **Learning Vector Quantization (LVQ)**. |
| `04-convolutional-networks/` | **CNN** fundamentals and a **LeNet-5** challenge on Fashion-MNIST.\* |
| `05-vision-transformer/` | A **Vision Transformer (ViT)** on Fashion-MNIST.\* |
| `runs/` | Trained-model artifacts for the Fashion-MNIST CNN (see below). |

\* Course challenge (*reto*) built as a team: Diego Arias, Jose Rojas, Josh Haberkern, Steffany Lara.

## Highlighted result — Fashion-MNIST CNN
The `runs/` folder ships a trained model and its full evaluation:
- **Test accuracy: 87.1%** · **Top-3 accuracy: 98.6%**
- `best_model.h5` (trained weights), `confusion_matrix.png`, `training_curves.png`, per-class metrics in `evaluation_report.json`, and `training_log.csv`.

## Tech stack
Python · TensorFlow / Keras · NumPy · pandas · scikit-learn · Matplotlib · seaborn

## Setup
```bash
pip install -r requirements.txt
```
> Datasets (e.g. Fashion-MNIST) are loaded via framework utilities and are not stored in this repo.

## Author
**Steffany Lara** — Data Science & Mathematics Engineering, Tecnológico de Monterrey. Team challenges co-authored as noted above.
