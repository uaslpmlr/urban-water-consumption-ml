# IoT-Based Monitoring and Machine Learning Classification of Urban Water Consumption Patterns

## Manuscript Information

**Journal:** IEEE Latin America Transactions

**Manuscript ID:** 10711

## Authors

Jose Martin Luna-Rivera¹,
Carlos A. Hernández-Morales¹,
Luis E. Baez-Salazar¹,
Javier Rufo²,
Jose Rabadan³

¹ Universidad Autónoma de San Luis Potosí, Mexico

² Universidad de La Laguna, Spain

³ Universidad de Las Palmas de Gran Canaria, Spain

---

## Repository Description

This repository contains all datasets and Jupyter notebooks required to reproduce the figures, tables, and machine learning results reported in the paper.

The code has been organized so that each notebook reproduces one or more figures or tables presented in the manuscript.

---
## Repository Structure

```text
urban-water-consumption-ml/
│
├── data/
│   ├── Ini23NovFin30Abril.csv
│   ├── Dataset_Consumo_Shifts_v2.xlsx
│   ├── Dataset_Consumo_Label_v1.xlsx
│   └── README.md
│
├── results/
│   ├── Figure_3_Daily_Time_Series.ipynb
│   ├── Figure_4_Daily_Distribution.ipynb
│   ├── Figure_5_Dominant_Shift.ipynb
│   ├── Figure_6_Weekly_Pattern.ipynb
│   ├── Figure_7_Label_Distribution.ipynb
│   ├── Figure_8_Unsupervised_Analysis.ipynb
│   ├── Figure_9_Supervised_Models.ipynb
│   ├── Table_VI_Performance.ipynb
│   └── README.md
│
├── README.md
├── requirements.txt
└── LICENSE
```

## Data Description

| File | Description |
|------|-------------|
| Ini23NovFin30Abril.csv | Original water consumption dataset. |
| Dataset_Consumo_Shifts_v2.xlsx | Dataset used for operational shift analysis. |
| Dataset_Consumo_Label_v1.xlsx | Labeled dataset used for machine learning experiments. |

## Notebooks

| Notebook | Output reproduced |
|----------|-------------------|
| Figure3_Daily_TimeSeries.ipynb | Figure 3 |
| Figure4_Distribution.ipynb | Figure 4 |
| Figure5_Dominant_Shift.ipynb | Figure 5 |
| Figure6_Weekly_Pattern.ipynb | Figure 6 |
| Figure7_Label_Distribution.ipynb | Figure 7 |
| Figure8_Unsupervised.ipynb | Figure 8 |
| Figure9_Supervised.ipynb | Figure 9 |
| TableVI.ipynb | Table VI |

## Requirements

The required Python packages are listed in

requirements.txt

Install them with

pip install -r requirements.txt


## Reproducing the Results

1. Clone the repository.

2. Install the required packages.

3. Execute the notebooks stored in the `results` directory.

The notebooks automatically load the datasets stored in the `data` directory.


## Repository

https://github.com/uaslpmlr/urban-water-consumption-ml

## Citation

If you use this repository, please cite the associated publication.



