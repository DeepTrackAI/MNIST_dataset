# MNIST Dataset (MNIST_dataset)

## Overview

This DeepTrackAI repository provides a copy of the **MNIST** dataset, a benchmark collection of handwritten digits originally created by Yann LeCun, Corinna Cortes, and Christopher J.C. Burges, originally available from the [Official MNIST Website](http://yann.lecun.com/exdb/mnist/).

Each image is a grayscale depiction of a digit from 0 to 9, with an associated label. MNIST is one of the most widely used datasets for training and evaluating machine learning and deep learning models in computer vision.

### Summary
- **Number of images**: 70,000 (60,000 training, 10,000 test)  
- **Image size**: 28 × 28 pixels  
- **Image format**: 8-bit grayscale PNG
- **Labels**: 10 classes (digits 0–9)  

---

## Original Source

- **Title**: The MNIST Database of Handwritten Digits  
- **Authors**: Yann LeCun, Corinna Cortes, Christopher J.C. Burges  
- **Source**: [Official MNIST Website](http://yann.lecun.com/exdb/mnist/)
- **Reference article**: LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. *Proceedings of the IEEE* 86(11): 2278-2324 (1998). [DOI: 10.1109/5.726791](https://doi.org/10.1109/5.726791) 
- **License**: [Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)](https://creativecommons.org/licenses/by-sa/3.0/)
- **Note**: The original MNIST website is no longer actively maintained. An [archived version](https://web.archive.org/web/20200430193701/http://yann.lecun.com/exdb/mnist/) is available, and the dataset is widely mirrored (e.g., on Kaggle).
  
If you use this dataset in your research, please follow the licensing requirements and properly attribute the original authors.

---

## Dataset Structure

```bash
/MNIST_dataset
└── mnist/
    ├── train/          # Training images (labeled by filename)
    │   ├── 0_000000.png
    │   ├── 0_000001.png
    │   └── ...
    └── test/           # Test images (labeled by filename)
        ├── 0_000000.png
        ├── 0_000001.png
        └── ...
```

Each filename begins with its class label (0–9), followed by a sequential numerical identifier.

---

## How to Access the Data

### Clone the Repository
```bash
git clone github.com/DeepTrackAI/MNIST_dataset
cd MNIST_dataset
```

---

## Attribution

If you use this dataset, please cite both the MNIST dataset and the reference article.

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

### Cite the reference article:
LeCun Y, Bottou L, Bengio Y, Haffner P. *Gradient-based learning applied to document recognition.* Proceedings of the IEEE, 86(11): 2278–2324 (1998). [DOI: 10.1109/5.726791](https://doi.org/10.1109/5.726791)

```bibtex
@article{lecun1998gradient,
  title     = {Gradient-based learning applied to document recognition},
  author    = {LeCun, Yann and Bottou, L{\'e}on and Bengio, Yoshua and Haffner, Patrick},
  journal   = {Proceedings of the IEEE},
  volume    = {86},
  number    = {11},
  pages     = {2278--2324},
  year      = {1998},
  publisher = {IEEE},
  doi       = {10.1109/5.726791}
}
```

---

## License

This replication dataset is shared under the [Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)](https://creativecommons.org/licenses/by-sa/3.0/) License, following the original licensing terms.
