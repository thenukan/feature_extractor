# Feature Extractor

This repository is modified from [Meta-Baseline: Exploring Simple Meta-Learning for Few-Shot Learning](https://arxiv.org/abs/2003.04390).

### Feature Output
(Mini-ImageNet features can be downloaded [here](https://drive.google.com/drive/folders/1AH7zJd6SkgXmZ8d1NhJmgqV_07AMOWOz?usp=sharing))

### Environment
- Python 3.7.3
- PyTorch 1.2.0
- TensorBoardX

### Datasets
(Mini-ImageNet data can be downloaded [here](https://drive.google.com/drive/folders/1fqZscEs2ttEKqFXAhuB6hBwyvFYEpIoR?usp=sharing))

### Generate Features
To generate features, run the following command:

```bash
python feature.py --config configs/train_classifier_mini.yaml
