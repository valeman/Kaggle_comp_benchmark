# Kaggle_comp_benchmark
Benchmark of tabular dataset using kaggle competition

| Score (Cross validation / Pubic / Private ) | Default Risk (AUC ↑)        | Fraud Detection (AUC ↑)        | Customer Satisfaction (AUC ↑)  | Safe Driver Prediction (Gini↑) |
|------------------------------|-----------------------------|--------------------------------|--------------------------------|--------------------------------|
| Logistic                     | 0.51440 / 0.55504 / 0.53800 | 0.742576 / 0.803224 / 0.752711 | 0.553412 / 0.52249 / 0.51959   | 0.18953 / 0.18725 / 0.19470    |
| Random Forest                | 0.73676 / 0.73359 / 0.73273 | 0.943387 / 0.944480 / 0.914231 | 0.756067 / 0.76580 / 0.76160   | 0.17171 / 0.20150 / 0.21191    |
| MLP                          | 0.67672 / 0.71152 / 0.71964 | 0.879579 / 0.910946 / 0.852730 | 0.767340 / 0.80079 / 0.78442   | 0.14097 / 0.19008 / 0.19936    |
| 1D-CNN                       | 0.71816 / 0.74979 / 0.75524 | 0.841671 / 0.865416 / 0.814458 | 0.821149 / 0.82849 / 0.81163   | 0.21196 / 0.23523 / 0.24516    |
| Gradient boosting (untuned)  | 0.78889 / 0.79300 / 0.78927 | 0.94401 / 0.950708 / 0.927236  | 0.789344 / 0.80332 / 0.78300   | 0.27938 / 0.27799 / 0.28117    |
| Gradient boosting (original) | 0.79848 / 0.80028 / 0.79741 | 0.96272 / 0.959638 / 0.931280  | 0.841088 / 0.83987 / 0.82655   | 0.28731 / 0.28553 / 0.29039    |
