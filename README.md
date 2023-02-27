# Time-series Forecasting

1. [Data](#data)
2. [Results](#results)
   - [General Sales Forecast](#general)
   - [Sales Forecast by Store](#store)
3. [Report Compilation](#report)

## 1) <a id='data'></a> Data

Kaggle-dataset: [Ecuadorin-based grocery retail store](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)

## 2) <a id='results'></a> Results

### 2.1) <a id='general'></a> General Sales Forecast

<div align="center">
<img src="https://github.com/razielar/forecasting_retail-store/blob/main/report/plots/forecast/forecast_prophet.png" alt="logo"></img>
</div>

### 2.2) <a id='store'></a> Sales Forecast by Store

<div align="center">
<img src="https://github.com/razielar/forecasting_retail-store/blob/main/report/plots/forecast/forecast_bystore.png" alt="logo" width=3400 height=2000 ></img>
</div>

## 3) <a id='report'></a> Report Compilation

### 3.1) Installation

Assumming you're using a Debian/Linux OS system you need to install `LaTEX` and `biber` (for bibliography):

* LaTEX:

``` bash

sudo apt install texlive-latex-extra

```

* biber:

``` bash

sudo apt install texlive-bibtex-extra biber

```

### 3.2) Report Compilation

To compile the file you need to do the following:

```{bash}

git clone https://github.com/razielar/forecasting_retail-store
cd report
./buildReport.sh

```
The bash-script will generate the **pdf.output** directory with the Report compliled.

