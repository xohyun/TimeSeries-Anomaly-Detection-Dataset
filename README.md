# TimeSeries-Anomaly-Detection-Dataset

Time series public data preprocessing and visualization code for anomaly detection

- Data preprocessing

  - [WADI](https://itrust.sutd.edu.sg/testbeds/water-distribution-wadi/)

  - [MSL](https://github.com/khundman/telemanom)
  - [SMAP](https://github.com/khundman/telemanom)

  - [NAB](https://github.com/numenta/NAB)

  - [SMD](https://github.com/NetManAIOps/OmniAnomaly)

- Visualization

<br>

## Data preprocessing

If you execute code 'Data_preprocessing.ipynb', you will finally get folder '**data**'. The example data folder is organized as follows.

```
data
 ├── WADI
 │    └── train, test, and labels of each data
 │    
 ├── MSL
 │    ├── C-2_labels.npy
 │    ├── C-2_test.npy
 │    └── C-2_train.npy
 │
 ├── SMAP
 │    ├── A-4_labels.npy
 │    ├── A-4_test.npy
 │    ├── A-4_train.npy
 │    ├── T-1_labels.npy
 │    ├── T-1_test.npy
 │    └── T-1_train.npy
 │
 ├── NAB
 │    └── train, test, and labels of each data
 │
 └── SMD
      └── train, test, and labels of each data
```



- Min-Max Normalization

- Save train, test and labels data in numpy data format

<br>

## Visualization

