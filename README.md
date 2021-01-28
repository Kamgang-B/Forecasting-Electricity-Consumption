# Project: Forecasting Electricity Consumption
_Forecasting Electricity Consumption_ is a low-scale small project that aims at forecasting electricity consumption for buildings
using univariate exponential smoothing, NNAR (neural network auto-regressive), and ARIMA models. Will also consider multivariate
dynamic regression, NNAR, and VAR models.

Model selection is mainly based on cross-validation technique; and model performance is measured using mean square error.

A relatively detail report about this forecasting can be found [HERE](https://github.com/kaboc7/Forecasting-Electricity-Consumption/blob/main/reports/Report.pdf)

# Repository structure

```
Forecasting Electricity Consumption/
├── data
│   ├── external
│   ├── interim
│   ├── processed
│   └── raw
├── docs
├── models
├── notebooks
├── references
├── reports
│   └── figures
└── src
    ├── data
    └── features
```