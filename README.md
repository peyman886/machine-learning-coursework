# Machine Learning — Coursework

Assignments and projects from two Machine Learning courses. Every assignment is
a Jupyter notebook committed with its outputs.

## 1402-1 · Dr. Bahrak

| Folder | Topic |
|---|---|
| [`HW01`](1402-1-bahrak/HW01) | End-to-end ML project: framing, cleaning, feature scaling, a first model (insurance data) |
| [`HW02`](1402-1-bahrak/HW02) | Classification: metrics, adult income, glass, mobile price |
| [`HW03`](1402-1-bahrak/HW03) | Multivariate least squares, L1/L2 regularization |
| [`HW04`](1402-1-bahrak/HW04) | Support vector machines and decision trees |
| [`HW05`](1402-1-bahrak/HW05) | PCA for classification, randomized PCA, t-SNE and UMAP |
| [`HW06`](1402-1-bahrak/HW06) | Clustering: k-means, DBSCAN, image segmentation |
| [`Project`](1402-1-bahrak/Project) | Final project: comparing optimizers, SAM and mixup across datasets and models |

## 1400-1 · Dr. Hosseini

| Folder | Topic |
|---|---|
| [`HW2`](1400-1-hosseini/HW2) | Data visualization and exploratory analysis (in Persian) |
| [`HW3`](1400-1-hosseini/HW3) | Linear, polynomial and RBF-kernel regression |
| [`HW4`](1400-1-hosseini/HW4) | Classification and hyperparameter tuning |
| [`Project`](1400-1-hosseini/Project) | Course project (tabular modelling with XGBoost/LightGBM), done with Reza Bagheri |

## Datasets

Public datasets are not stored in this repository. To re-run a notebook, download
the dataset and save it next to the notebook under the file name shown.

| File expected | Used in | Source |
|---|---|---|
| `insurance.csv` | 1402-1 HW01 | Medical Cost Personal Dataset — [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance) |
| `adult.csv` | 1402-1 HW02 | Adult (census income), UCI — [link](https://archive.ics.uci.edu/dataset/2/adult) |
| `glass.csv` | 1402-1 HW02 | Glass Identification, UCI — [link](https://archive.ics.uci.edu/dataset/42/glass+identification) |
| `mobile price/train.csv`, `test.csv` | 1402-1 HW02 | Mobile Price Classification — [Kaggle](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification) |
| `boston_housing.csv` | 1402-1 HW03 | Boston Housing — [StatLib](http://lib.stat.cmu.edu/datasets/boston) |
| `Diabetes.csv` | 1402-1 HW04 | Pima Indians Diabetes — [OpenML](https://www.openml.org/d/37) (columns renamed to `pregnant, glucose, BP, skin, insulin, BMI, pedigree, age, label`) |
| `oj.csv` | 1402-1 HW04 | `OJ` from the ISLR package — [docs](https://vincentarelbundock.github.io/Rdatasets/doc/ISLR/OJ.html) |
| `Carseats.csv` | 1402-1 HW05 | `Carseats` from the ISLR package — [docs](https://vincentarelbundock.github.io/Rdatasets/doc/ISLR/Carseats.html) |
| `bank_marketing_dataset.csv` | 1402-1 HW06 | Bank Marketing, UCI — [link](https://archive.ics.uci.edu/dataset/222/bank+marketing) |
| `CC GENERAL.csv` | 1402-1 HW06 | Credit Card Dataset for Clustering — [Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata) |
| `Wholesale customers data.csv` | 1402-1 HW06 | Wholesale customers, UCI — [link](https://archive.ics.uci.edu/dataset/292/wholesale+customers) |
| `dataset.csv` | 1400-1 HW2 | `CreditCard` from the AER package — [docs](https://vincentarelbundock.github.io/Rdatasets/doc/AER/CreditCard.html) |
| `mnist.zip` | 1400-1 HW2 | MNIST — [Hugging Face](https://huggingface.co/datasets/ylecun/mnist) |

Small course-provided files (`1402-1-bahrak/HW04/Data.csv`, `1400-1-hosseini/HW4/data.csv`,
the project result tables) are kept in the repository.

## Papers and code used in the final project (1402-1)

- P. Foret et al. — *Sharpness-Aware Minimization for Efficiently Improving Generalization*, ICLR 2021 — [arXiv:2010.01412](https://arxiv.org/abs/2010.01412)
- H. Zhang et al. — *mixup: Beyond Empirical Risk Minimization*, ICLR 2018 — [arXiv:1710.09412](https://arxiv.org/abs/1710.09412)
- SAM / ASAM optimizer for PyTorch — [davda54/sam](https://github.com/davda54/sam)

`Project/resources/image-filenames.txt` lists the images of the project dataset.
