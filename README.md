![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![ScikitLearn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

# Global Homicide Rates — Machine Learning Analysis

🔗 Dataset pubblicato su Kaggle:  
https://www.kaggle.com/datasets/lucalullo/global-homicide-rates-by-country

## 📊 Notebook di analisi
👉 https://www.kaggle.com/code/lucalullo/predicting-homicide

Questo progetto presenta un'analisi esplorativa e un esempio di modellazione predittiva sui **tassi di omicidio globali**, utilizzando dati per paese, sesso, gruppo di età e anno.

L’obiettivo del notebook è dimostrare come tecniche di **data analysis e machine learning** possano essere applicate per esplorare pattern nei dati e stimare il tasso di omicidi (per 100.000 abitanti) a partire da variabili demografiche e temporali.

## Obiettivi

- Analizzare la distribuzione dei tassi di omicidio tra paesi
- Esplorare differenze tra gruppi di età e sesso
- Studiare le dinamiche temporali dei tassi di omicidio
- Costruire un modello di **machine learning** per stimare i tassi di omicidio
- Valutare le prestazioni del modello tramite metriche di regressione

## Dataset

Il dataset contiene osservazioni sui **tassi di omicidio per 100.000 abitanti** per diversi paesi e gruppi demografici.

Variabili principali:

- `iso_code` — codice ISO del paese  
- `country` — nome del paese  
- `year` — anno di osservazione  
- `sex` — sesso  
- `age_group` — gruppo di età  
- `homicide_rate` — tasso di omicidi per 100.000 abitanti  

I dati consentono di confrontare le dinamiche della criminalità tra paesi e gruppi demografici.

## Modello di Machine Learning

Nel notebook viene addestrato un modello **Random Forest Regressor** per stimare il tasso di omicidi utilizzando le variabili disponibili.

Il modello apprende la relazione tra:

(country, year, sex, age_group) → homicide_rate

Le prestazioni del modello sono valutate tramite metriche di regressione come:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R²

## Contenuto della repository

- Notebook Python con analisi dei dati
- Implementazione del modello di machine learning
- Visualizzazioni e valutazione delle predizioni

## Tecnologie utilizzate

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Disclaimer

Questo progetto è realizzato **a scopo illustrativo e didattico**.  
Il modello di machine learning presentato è una dimostrazione tecnica e non deve essere interpretato come uno strumento affidabile per prevedere l’andamento reale degli omicidi.

Le dinamiche della criminalità dipendono da numerosi fattori sociali, economici e istituzionali che non sono inclusi in questo dataset.

## Autore
Luca Lullo
