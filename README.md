# Introduction to AI Courses

This repository contains teaching material and hands-on exercises for an introductory Artificial Intelligence course. The content is organized by course session and combines lecture slides with Jupyter notebooks focused on core machine learning and deep learning concepts.

## Repository Content

```text
.
├── cours-1/
│   ├── Introduction.pdf
│   └── linear_regression_from_scratch_exercises.ipynb
├── cours-2/
│   ├── Neural Network.pdf
│   └── lineare_and_cnn_exercice.ipynb
└── README.md
```

## Course 1 — Linear Regression from Scratch

The first course introduces foundational AI and machine learning concepts, then focuses on implementing linear regression without relying on high-level machine learning libraries.

### Materials

- `cours-1/Introduction.pdf` — introductory lecture slides.
- `cours-1/linear_regression_from_scratch_exercises.ipynb` — practical notebook on linear regression.

### Topics Covered

- Synthetic data generation for regression tasks.
- Linear regression with one feature.
- Model implementation from scratch.
- Training loops, loss computation, and gradient-based optimization.
- Effects of initialization, number of epochs, and learning rate.
- Linear regression with two features.
- Feature scaling issues and normalization.

## Course 2 — From Linear Layers to Convolutional Neural Networks

The second course introduces neural networks and image classification, moving from linear models to convolutional neural networks using CIFAR-10.

### Materials

- `cours-2/Neural Network.pdf` — lecture slides about neural networks.
- `cours-2/lineare_and_cnn_exercice.ipynb` — practical notebook comparing linear models and CNNs.

### Topics Covered

- CIFAR-10 dataset loading and visualization.
- Image input representations.
- Linear model implementation and training.
- Error analysis for image classification.
- Deeper linear models.
- CNN model implementation and training.
- Comparison between linear models and CNNs.
- Suggested experiments for improving performance.

## Prerequisites

To work with the notebooks, you should be familiar with:

- Basic Python programming.
- Core NumPy operations.
- Basic calculus concepts such as gradients.
- Machine learning fundamentals such as training data, loss functions, and optimization.

## Recommended Environment

Use Python 3.10 or newer with Jupyter Notebook or JupyterLab.

### Python Packages

The notebooks use the following main packages:

- `numpy`
- `matplotlib`
- `scikit-learn`
- `torch`
- `torchvision`
- `jupyter`

You can install them with:

```bash
python -m pip install numpy matplotlib scikit-learn torch torchvision jupyter
```

> Note: depending on your operating system and hardware, you may want to install PyTorch using the official command generated for your platform from the PyTorch website.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Introduction-to-AI-courses.git
   cd Introduction-to-AI-courses
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

   On Windows, use:

   ```powershell
   .venv\Scripts\activate
   ```

3. Install the required packages:

   ```bash
   python -m pip install numpy matplotlib scikit-learn torch torchvision jupyter
   ```

4. Start Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open the notebooks from `cours-1/` or `cours-2/` and follow the exercises.

## Suggested Learning Path

1. Read the introductory slides in `cours-1/Introduction.pdf`.
2. Complete `cours-1/linear_regression_from_scratch_exercises.ipynb`.
3. Read `cours-2/Neural Network.pdf`.
4. Complete `cours-2/lineare_and_cnn_exercice.ipynb`.
5. Re-run experiments by changing hyperparameters such as learning rate, number of epochs, and model depth.

## Notes for Students

- Run notebook cells in order to avoid missing variables or imports.
- Try to complete each exercise before reading the provided answers.
- Experiment with hyperparameters and observe how training behavior changes.
- Keep track of your results and compare model performance across experiments.

## License

No license has been specified yet. Add a license file if you plan to distribute, reuse, or publish the material under specific terms.
