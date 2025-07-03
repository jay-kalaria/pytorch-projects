# 🔥 My PyTorch Learning Journey

Hey there! 👋 Welcome to my collection of PyTorch projects. I'm learning deep learning and computer vision, and this repo is basically my playground where I experiment with different models and datasets.

## What's in here?

### 🐱 Animal Image Classification

**Location:** `animal-image-classification/`

This is where I trained a neural network to tell apart cats, dogs, and wild animals! I used the AFHQ dataset from Kaggle (it's pretty cool - lots of high quality animal face images). The model can actually distinguish between the three categories pretty well.

**What I learned:**

-   Custom PyTorch datasets
-   Image preprocessing with torchvision
-   Building CNN models from scratch
-   Working with image data

### 📚 PyTorch Basics

**Location:** `basics-models/`

This is my "learning the ropes" notebook. I started here when I was figuring out what tensors are and how PyTorch works. It's got simple examples like:

-   Tensor operations (squeeze, unsqueeze - these confused me at first!)
-   A basic linear regression model
-   Setting up devices (MPS for Mac, CUDA for GPU)

Perfect if you're just starting out like I was!

### 🌾 Rice Classification

**Location:** `rice-classification-project/`

Not all machine learning is about images! This project classifies different types of rice using tabular data (features like area, length, roundness, etc.). It's a binary classification problem with a simple neural network.

**What I learned:**

-   Working with CSV/tabular data in PyTorch
-   Data normalization techniques
-   Simple feedforward neural networks
-   Binary classification

## Getting Started

Most of these projects use Jupyter notebooks, so just:

1. Clone this repo
2. Install the requirements (PyTorch, torchvision, matplotlib, pandas, etc.)
3. Open the `.ipynb` files and run them!

Some projects download datasets from Kaggle, so you might need to set up your Kaggle API credentials.

## My Setup

I'm running this on a Mac with Apple Silicon, so you'll see `device = "mps"` in a lot of places. If you're on a different system, PyTorch will automatically fall back to CPU or use CUDA if you have an NVIDIA GPU.

## Random Notes

-   These projects are learning exercises, so the code might not be perfect!
-   I tried to comment things that confused me when I was learning
-   Feel free to mess around with the hyperparameters and see what happens
-   Some datasets are pretty large, so downloads might take a while

Happy learning! 🚀

---

_This is just my personal collection of PyTorch experiments. If you're also learning ML/DL, hopefully you find some of this useful!_
