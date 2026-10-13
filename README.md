# Python for Data Science

The core Python data stack in practice: **NumPy** for numerical computing, **pandas** for data wrangling, **Matplotlib & Seaborn** for visualization, and a full **feature engineering** toolkit to prepare data for machine learning.

Every notebook runs in Google Colab: open it and click **"Open in Colab"** at the top.

**Tech:** Python · NumPy · pandas · Matplotlib · Seaborn · scikit-learn · imbalanced-learn

---

## 📚 Notebooks

### NumPy
| # | Topic |
|---|---|
| 01 | [Intro to NumPy](0001_Intro_to_Numpy.ipynb) |
| 02 | [NumPy Matrices](0002_Numpy_Matrixes.ipynb) |
| 03 | [NumPy Operations](0003_Numpy_Operations.ipynb) |

### pandas
| # | Topic | Dataset |
|---|---|---|
| 04 | [Intro to pandas](0004_Intro_to_Pandas.ipynb) | |
| 05 | [Intro to DataFrames](0005_IntroToDataFrame.ipynb) | |
| 06 | [DataFrame Operations](0006_DataFrameOperations.ipynb) | Employee data |
| 07 | [GroupBy](0007_Groupby_with_csv.ipynb) | Employee data |
| 08 | [Concat & Merge](0008_DataFrameConcatMarge.ipynb) | |
| 09 | [Apply Functions](0009_DataFrameApply.ipynb) | |

### Visualization & EDA
| # | Topic | Dataset |
|---|---|---|
| 10 | [Intro to Matplotlib](0010_IntroToMatplotlip.ipynb) | |
| 11 | [Matplotlib Styles](0011_MatplotlibStyles.ipynb) | |
| 12 | [Visualization with Seaborn](0012_VisualisationSeaborn.ipynb) | Olympic athletes (120 years) |
| 13 | [Box Plot Exercise](0013_BoxPlotExercise.ipynb) | Titanic |
| 14 | [**EDA: Wine Quality**](0014_EDA_WineQualityExercise.ipynb) | Wine Quality |

### Feature Engineering
| # | Topic | Dataset |
|---|---|---|
| 15 | [Missing Values](0015_IntroToFeatureEngineering.ipynb) | Titanic |
| 16 | [Balancing Imbalanced Data](0016_BalancingData.ipynb) | Synthetic (up/down-sampling, SMOTE) |
| 17 | [Encoding Categorical Data](0017_EncodingData.ipynb) | Titanic |
| 18 | [**Feature Engineering: Google Play Store**](0018_FeatureEngGooglePlayDataSet.ipynb) | Google Play apps |

---

## ▶️ Running locally

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn jupyter
jupyter notebook
```

Some notebooks load data from Google Drive (`/content/drive/...`). To run locally, download the dataset and update the `pd.read_csv(...)` path.

**Next step:** these skills are applied to modeling in [Machine-Learning-Applications](https://github.com/channel1umut-lang/Machine-Learning-Applications).
