# 🔥 PyTorch From Scratch

A hands-on collection of Jupyter notebooks for learning PyTorch from the ground up — from tensor basics to convolutional networks and transfer learning. Each notebook combines concise theory with progressive exercises designed to build real intuition.

The exercises throughout these notebooks were designed with the assistance of Claude (Anthropic's AI). All solutions and elaborations are my own work, guided by Claude. If you spot any mistakes — in the exercises or the solutions — feel free to open an issue or reach out.
---

## 📚 Contents

| # | Notebook | Topics |
|---|----------|--------|
| 00 | **Fundamentals** | Tensors, data types, shape manipulation, broadcasting, memory semantics, normalization |
| 01 | **Autograd & Gradients** | Computational graphs, backpropagation, gradient clipping, Jacobians, Hessians, custom `autograd.Function` |
| 02 | **Training & Data Pipelines** | `nn.Module`, `nn.Sequential`, optimizers, loss functions, custom layers, model saving & loading |
| 03 | **CNNs & Transfer Learning** | Convolutional blocks, pooling, training on MNIST, fine-tuning ResNet-18 on FashionMNIST |

Each topic is organised into levelled exercises (🐧 → 🐉) to guide you from foundational concepts to more advanced applications.

---

## 🗂️ Repository Structure

```
pytorch-from-scratch/
├── Notebooks/          # Notebooks with exercises (no solutions)
├── Solutions/          # Fully worked solutions
└── LICENSE
```

---

## ⚙️ Requirements

- Python ≥ 3.9
- PyTorch ≥ 2.0
- torchvision
- NumPy
- Matplotlib
- scikit-learn

Install everything at once:

```bash
pip install  -r requirements.txt
```

---

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/afdezcaravaca/pytorch-from-scratch.git
cd pytorch-from-scratch
```

2. Open a notebook:

```bash
jupyter notebook Notebooks/00_Fundamentals.ipynb
```

> It is recommended to work through the notebooks in order, as each one builds on concepts introduced in the previous one.

---

## 🧭 Recommended Learning Path

```
00_Fundamentals  ──►  01_Autograd_Gradients  ──►  02_Training_and_Data_Pipelines  ──►  03_CNNs_and_Transfer_Learning
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
