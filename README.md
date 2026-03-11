# RPA4WEB: 

## Directory Structure
The repository is organized as follows:

```text
data/
├──Eo2Json
  ├── train.xlsx       # Full training dataset (50,000 samples)
  ├── train_en.xlsx    # English-only training subset (~25,000 samples)
  ├── train_vi.xlsx    # Vietnamese-only training subset (~25,000 samples)
  └── test.xlsx        # Test set for final evaluation
├──DinhViPhanTu..
```
### Description:
**Eo2Json**:
- **train.xlsx**: The primary training dataset containing 50,000 samples with a balanced 1:1 ratio between Vietnamese and English.
- **train_en.xlsx** and **train_vi.xlsx**: Training data separated by language (English and Vietnamese).
- **test.xlsx**: A dataset used to calculate final performance metrics including Key Score, Value Score, and Satisfaction Score.
- **Training Size**: 50,000 samples.
- **Attribute coverage**: Includes approximately 150 common CSS properties.
