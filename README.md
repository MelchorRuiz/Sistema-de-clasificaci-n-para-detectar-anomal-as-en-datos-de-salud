# Tarea 2.3 — Detección de Anomalías en Datos de Salud

Clasificación de anomalías en señales biométricas (BPM, HRV, SpO2) mediante **KNN** con y sin **PCA**, usando datos simulados de un ESP32 (~4000 registros de ventanas de 5 min).

## Contenido

- `Tarea_2_3.ipynb` — Notebook con carga, preprocesamiento, entrenamiento de ambos modelos y comparativa.
- `datos_salud.csv` — Dataset con timestamp, media_bpm, rmssd_hrv, std_spo2 y etiqueta de anomalía.

## Requisitos

- pandas, numpy, scikit-learn, matplotlib, seaborn
