# Dataset Information

## Dataset: sklearn Digits

- **Source**: `sklearn.datasets.load_digits`
- **No download required**: The dataset is bundled with scikit-learn and loaded directly in the notebooks.
- **Size**: 1797 samples, 64 features (8x8 pixel images), 10 classes (digits 0-9)
- **Feature type**: Continuous integers (0-16), representing grayscale pixel intensities
- **Preprocessing**: StandardScaler (zero mean, unit variance) applied in each notebook
- **Train/Test Split**: 80/20, random_state=42

## Usage
The dataset is loaded in each notebook using:
```python
from sklearn.datasets import load_digits
digits = load_digits()
X, y = digits.data, digits.target
```

No manual data download or placement is needed. All notebooks are self-contained.
