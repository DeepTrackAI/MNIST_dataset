# MNIST Dataset (MNIST_dataset)

## Overview

This DeepTrackAI repository provides a copy of the **MNIST** dataset, a benchmark collection of handwritten digits originally created by Yann LeCun, Corinna Cortes, and Christopher J.C. Burges, available from the [Official MNIST Website](http://yann.lecun.com/exdb/mnist/).

MNIST is one of the most widely used datasets for training and evaluating machine learning and deep learning models in computer vision.

Each image is a grayscale depiction of a digit from 0 to 9, with an associated label. All images are 28×28 pixels in size. The dataset is split into a training set of 60,000 images and a test set of 10,000 images.

### Summary
- **Number of images**: 70,000 (60,000 training, 10,000 test)  
- **Image size**: 28×28 pixels  
- **Color**: Grayscale  
- **Labels**: 10 classes (digits 0–9)  
- **Format**: PNG, 8-bit per channel

---

## Original Source

- **Title:** The MNIST Database of Handwritten Digits  
- **Authors:** Yann LeCun, Corinna Cortes, Christopher J.C. Burges
- **Source:** [Official MNIST Website](http://yann.lecun.com/exdb/mnist/)  
- **License:** [Creative Commons Attribution-Share Alike 3.0](https://creativecommons.org/licenses/by-sa/3.0/)

If you use this dataset in your research, you must follow the licensing requirements and properly attribute the original authors.

---

## Dataset Structure

```bash
/MNIST_dataset  
  ├── train/          # Training images
  │   ├── 0_xxxxxx.png
  │   ├── 1_xxxxxx.png
  │   └── ...
  └── test/           # Test images
      ├── 0_xxxxxx.png
      ├── 1_xxxxxx.png
      └── ...
```

In each folder, the digit before the underscore in the filename corresponds to the image label.

---

## How to Access the Data

### Clone the Repository
```bash
git clone -b mnist github.com/DeepTrackAI/MNIST_dataset
cd MNIST_dataset
```

---

## Attribution

This replication dataset is based on the original MNIST dataset. When using this replication, please cite both the dataset and the original paper.

### Cite the dataset:
LeCun Y, Cortes C, Burges CJC. *The MNIST Database of Handwritten Digits.* Retrieved from [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/)

```bibtex
@misc{lecun1998mnist,
  title        = {The MNIST Database of Handwritten Digits},
  author       = {LeCun, Yann and Cortes, Corinna and Burges, Christopher J.C.},
  year         = {1998},
  howpublished = {\url{http://yann.lecun.com/exdb/mnist/}}
}
```

### Cite the original paper:
LeCun Y, Bottou L, Bengio Y, Haffner P. *Gradient-based learning applied to document recognition.* Proceedings of the IEEE, 86(11): 2278–2324 (1998). [https://doi.org/10.1109/5.726791](https://doi.org/10.1109/5.726791)

```bibtex
@article{lecun1998gradient,
  title     = {Gradient-based learning applied to document recognition},
  author    = {LeCun, Yann and Bottou, L{\'e}on and Bengio, Yoshua and Haffner, Patrick},
  journal   = {Proceedings of the IEEE},
  volume    = {86},
  number    = {11},
  pages     = {2278--2324},
  year      = {1998},
  publisher = {IEEE}
}
```

---

## License

This replication dataset is shared under the **Creative Commons Attribution-Share Alike 3.0** License, following the original licensing terms.
