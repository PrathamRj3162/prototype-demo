# 📊 Adult Income Dataset (Census Income Data)

**Description:**  
This dataset is used to predict whether income exceeds $50K/yr based on census data.  
It was extracted from the 1994 U.S. Census database.  
Commonly used for machine learning classification tasks.

---

## 📂 Files Included
| File Name | Description |
|------------|-------------|
| `adult.data` | Training data (32,561 rows) |
| `adult.test` | Testing data (16,281 rows) |
| `adult.names` | Attribute information and labels |
| `old.adult.names` | Original version of attribute info |
| `Index` | Index file for dataset reference |

---

## 📥 Direct Dataset Links
(Replace `<your-username>` with your GitHub username once uploaded)

- [adult.data](https://raw.githubusercontent.com/<your-username>/adult-dataset/main/adult.data)  
- [adult.test](https://raw.githubusercontent.com/<your-username>/adult-dataset/main/adult.test)  
- [adult.names](https://raw.githubusercontent.com/<your-username>/adult-dataset/main/adult.names)  
- [old.adult.names](https://raw.githubusercontent.com/<your-username>/adult-dataset/main/old.adult.names)  
- [Index](https://raw.githubusercontent.com/<your-username>/adult-dataset/main/Index)

---

## 🧠 Dataset Details

- **Number of Attributes:** 14 (including target variable)
- **Target Variable:** `income` (<=50K, >50K)
- **Type:** Mixed (Continuous + Categorical)
- **Missing Values:** Represented by '?'

---

## 📚 Citation
If you use this dataset, please cite:  
> Ronny Kohavi and Barry Becker (1996). “Adult Data Set.” UCI Machine Learning Repository.  
> [https://archive.ics.uci.edu/ml/datasets/adult](https://archive.ics.uci.edu/ml/datasets/adult)

---

## ⚙️ Example Usage (Python)
```python
import pandas as pd

# Load dataset
data = pd.read_csv("https://raw.githubusercontent.com/<your-username>/adult-dataset/main/adult.data",
                   header=None, names=["age","workclass","fnlwgt","education","education-num",
                                       "marital-status","occupation","relationship","race",
                                       "sex","capital-gain","capital-loss","hours-per-week",
                                       "native-country","income"])

print(data.head())
```
