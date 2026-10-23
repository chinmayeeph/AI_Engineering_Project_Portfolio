# 🧠 Deep Learning Projects

A collection of hands-on projects focused on building, training, evaluating, and deploying neural network models using Python and modern Deep Learning frameworks.

This folder documents my journey from understanding neural network fundamentals to developing practical applications in computer vision, sequence modeling, representation learning, and other deep learning domains.

> **Current status:** Project ideas and learning roadmap. Each project will be marked as completed as it is implemented, evaluated, and documented.

---

## 🎯 Objectives

- Understand artificial neural networks and how they learn.
- Implement forward propagation and backpropagation conceptually.
- Learn activation functions, loss functions, and optimizers.
- Build and train neural networks using PyTorch.
- Understand training, validation, and test datasets.
- Identify overfitting and improve model generalization.
- Explore computer vision and image classification.
- Learn embeddings and representation learning.
- Understand sequence modeling and attention fundamentals.
- Apply transfer learning to practical problems.
- Build reproducible deep learning training pipelines.
- Prepare for NLP, Generative AI, and AI Engineering.

---

## 🧰 Technologies

- **Language:** Python
- **Primary framework:** PyTorch
- **Alternative framework:** TensorFlow/Keras
- **Data processing:** NumPy, Pandas
- **Computer vision:** Torchvision, Pillow, OpenCV
- **Visualization:** Matplotlib, Seaborn
- **Experiment tracking:** MLflow or TensorBoard
- **Development tools:** Jupyter Notebook, VS Code, Google Colab
- **Testing:** pytest
- **Version control:** Git and GitHub

> **Learning approach:** Start with PyTorch and small datasets. Google Colab can provide access to a GPU for eligible sessions, but GPU availability and usage limits may vary. A GPU is not required for every beginner project.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced.

### 🟢 Beginner Projects

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 01 | Perceptron from Scratch | Neurons, weights, bias, decision boundaries | Planned |
| 02 | Neural Network from Scratch | Forward propagation, loss, gradient descent | Planned |
| 03 | Handwritten Digit Classification | Fully connected neural networks, MNIST | Planned |
| 04 | Fashion Item Classification | Multiclass classification, evaluation | Planned |
| 05 | Binary Image Classifier | Binary classification, training loops | Planned |
| 06 | Neural Network Activation Explorer | ReLU, sigmoid, tanh, softmax | Planned |
| 07 | Loss Function Comparison | Cross-entropy, MSE, learning behavior | Planned |
| 08 | Overfitting Demonstration Lab | Train/validation curves, regularization | Planned |

### 🟡 Intermediate Projects

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 09 | CNN Image Classification | Convolution, pooling, feature maps | Planned |
| 10 | Transfer Learning Image Classifier | Pretrained models, fine-tuning | Planned |
| 11 | Plant Disease Image Classification | Image preprocessing, multiclass prediction | Planned |
| 12 | Food Image Classification | CNNs, augmentation, evaluation | Planned |
| 13 | Sentiment Classification with Embeddings | Embeddings, text preprocessing | Planned |
| 14 | Sequence Modeling with LSTM | Recurrent networks, sequence data | Planned |
| 15 | Autoencoder for Image Reconstruction | Latent representations, reconstruction loss | Planned |
| 16 | Denoising Autoencoder | Noise removal, representation learning | Planned |
| 17 | Image Data Augmentation Study | Generalization, augmentation strategies | Planned |
| 18 | Hyperparameter Tuning Experiment | Learning rates, batch sizes, optimizers | Planned |

### 🔴 Advanced Projects

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 19 | Custom CNN Architecture Benchmark | Architecture design, model comparison | Planned |
| 20 | Image Segmentation Prototype | Pixel-level prediction, segmentation metrics | Planned |
| 21 | Object Detection Introduction | Bounding boxes, detection evaluation | Planned |
| 22 | Attention Mechanism Explorer | Query, key, value concepts | Planned |
| 23 | Vision Transformer Image Classifier | Patch embeddings, self-attention | Planned |
| 24 | Contrastive Learning Prototype | Similarity learning, embedding spaces | Planned |
| 25 | Deep Learning Experiment Tracker | Metrics, checkpoints, reproducibility | Planned |
| 26 | Model Compression Benchmark | Quantization concepts, inference performance | Planned |
| 27 | Deep Learning Inference API | Model loading, input validation, prediction API | Planned |
| 28 | End-to-End Deep Learning Pipeline | Data preparation, training, evaluation, inference | Planned |

---

## 📚 Concepts Covered

### 1. Neural Network Fundamentals
- Neurons, weights, and biases
- Layers and network architecture
- Forward propagation
- Loss functions
- Backpropagation
- Gradient descent
- Learning rates and batch sizes

### 2. Activation and Loss Functions
- Sigmoid
- Tanh
- ReLU and related variants
- Softmax
- Mean Squared Error
- Binary Cross-Entropy
- Cross-Entropy Loss

### 3. Training and Optimization
- Stochastic Gradient Descent
- Adam optimizer
- Mini-batch training
- Epochs and iterations
- Learning-rate scheduling
- Weight initialization
- Gradient clipping

### 4. Generalization and Regularization
- Overfitting and underfitting
- Train, validation, and test splits
- Dropout
- Weight decay
- Early stopping
- Data augmentation
- Class imbalance
- Error analysis

### 5. Computer Vision
- Image representation as tensors
- Convolution and pooling
- Feature maps
- Convolutional Neural Networks (CNNs)
- Image normalization
- Data augmentation
- Transfer learning
- Image classification and segmentation fundamentals

### 6. Embeddings and Sequence Models
- Word and token embeddings
- Sequential data
- Recurrent Neural Networks
- LSTM and GRU
- Padding and batching sequences
- Attention fundamentals
- Embedding visualization

### 7. Advanced Architectures
- Autoencoders
- Attention mechanisms
- Transformers
- Vision Transformers
- Contrastive learning
- Representation learning
- Model compression concepts

### 8. Reproducibility and Deployment
- Random seeds
- Saving and loading model checkpoints
- Training logs and metrics
- Experiment tracking
- CPU versus GPU execution
- Batch inference
- Model evaluation in production-like settings
- Basic prediction APIs

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
10_Deep_Learning_Projects/
│
├── README.md
│
├── 01_perceptron_from_scratch/
│   ├── README.md
│   ├── notebooks/
│   ├── src/
│   ├── tests/
│   └── outputs/
│
├── 02_neural_network_from_scratch/
│   ├── README.md
│   ├── notebooks/
│   ├── src/
│   ├── tests/
│   └── outputs/
│
├── 03_handwritten_digit_classification/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   ├── models/
│   ├── tests/
│   └── outputs/
│
└── ...
```

**Folder guidelines:**

- `data/` — datasets or instructions for downloading them; avoid committing large datasets.
- `notebooks/` — experiments and visual explanations.
- `src/` — reusable model, training, evaluation, and inference code.
- `models/` — saved checkpoints when appropriate; avoid committing large model files.
- `tests/` — tests for preprocessing, tensor shapes, and important functions.
- `outputs/` — charts, metrics, and sample predictions.
- `README.md` — problem statement, dataset, architecture, training process, results, and limitations.

For beginner projects, a single notebook and README are sufficient. Introduce separate modules as your code becomes more complex.

---

## ✅ Project Completion Checklist

- [ ] Define the problem and expected model output.
- [ ] Document the dataset source and permitted usage.
- [ ] Inspect and preprocess the data.
- [ ] Establish a simple baseline where appropriate.
- [ ] Define the model architecture.
- [ ] Select a suitable loss function and optimizer.
- [ ] Separate training, validation, and test data appropriately.
- [ ] Train the model and track relevant metrics.
- [ ] Evaluate on data not used for model fitting or tuning.
- [ ] Inspect incorrect predictions and failure cases.
- [ ] Check for overfitting and data leakage.
- [ ] Document architecture and training decisions.
- [ ] Save the model and inference instructions when needed.
- [ ] Add tests for important components.
- [ ] Document limitations and reproducibility steps.
- [ ] Commit the completed project to GitHub.

---

## 🗺️ Recommended Learning Order

1. **Perceptron from Scratch** — understand the basic artificial neuron.
2. **Neural Network from Scratch** — build intuition for forward propagation and gradient descent.
3. **Handwritten Digit Classification** — train your first neural network using PyTorch.
4. **Fashion Item Classification** — improve multiclass classification.
5. **Overfitting Demonstration Lab** — understand generalization.
6. **CNN Image Classification** — learn image-specific neural network architectures.
7. **Transfer Learning Image Classifier** — use pretrained models effectively.
8. **Sentiment Classification with Embeddings** — explore text representations.
9. **Attention Mechanism Explorer** — prepare for Transformers and Generative AI.
10. **End-to-End Deep Learning Pipeline** — combine training, evaluation, and inference.

**Recommendation:** Learn the fundamentals of neural networks before attempting Transformers. You do not need to master every mathematical derivation immediately, but you should understand what the main components do and how they affect learning.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 28 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with documented evaluation | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [NumPy Projects](../03_NumPy_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [Statistics Projects](../06_Statistics_Projects/README.md)
- [EDA and Visualization Projects](../07_EDA_Visualization_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)
- [NLP Projects](../11_NLP_Projects/README.md)
- [Generative AI and RAG Projects](../12_Generative_AI_RAG_Projects/README.md)
- [Deployment, Cloud, and MLOps](../15_Deployment_Cloud_MLOps/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Understand the data → Build the model → Train carefully → Evaluate honestly → Investigate errors → Improve generalization → Prepare reliable inference.**

The goal is not simply to build a neural network that produces a high score. It is to understand how it learns, evaluate how well it generalizes, and document its limitations clearly.
