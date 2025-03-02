# My First ANN with Fashion-MNIST

## Overview

This repository contains my first Artificial Neural Network (ANN) project using the **Fashion-MNIST** dataset. The project includes theoretical notes and practical implementations of neural networks for image classification.

## Dataset

The **Fashion-MNIST** dataset is a collection of 70,000 grayscale images of 10 different categories of clothing items. It serves as a benchmark dataset for machine learning and deep learning applications.

-   **Source**: Fashion-MNIST is a dataset provided by Zalando Research.
-   **License**: Fashion-MNIST is licensed under the [MIT License](https://github.com/zalandoresearch/fashion-mnist/blob/master/LICENSE).
-   **Official Repository**: [Fashion-MNIST GitHub](https://github.com/zalandoresearch/fashion-mnist)
-   **Citation**: If you use this dataset, please cite the following paper:
    ```
    @article{xiao2017/online,
      author    = {Han Xiao and Kashif Rasul and Roland Vollgraf},
      title     = {Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms},
      year      = {2017},
      url       = {https://arxiv.org/abs/1708.07747}
    }
    ```

## Project Structure

```
├── data/                 # Contains Fashion-MNIST dataset
├── notebooks/            # Jupyter notebooks for experiments
├── models/               # Saved neural network models
├── src/                  # Source code for training and evaluation
├── README.md             # This file
```

## Installation

To run the project, install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the training script:

```bash
python src/train.py
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

-   Thanks to Zalando Research for providing the Fashion-MNIST dataset.
-   Inspired by TensorFlow and PyTorch tutorials.

---

Feel free to modify this README based on your project's specific details!
