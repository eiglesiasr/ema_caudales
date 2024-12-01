# ema_caudales
Proyecto Final Estadística Multivarada Avanzada - Univerdidad EAFIT Semestre 2024-2

## Presentado Por:
- Edgard Iglesias Rubio
- Harold Nolberto Díaz Giraldo

Por el nivel de confidencialidad de los datos no se comparte repositorio, sino que se comparte una carpeta compartida, así mismo no es posible compartir los datos sino únicamente el código para interactuar con los datos, la estructura de la carpeta compartida es la siguiente:

## Objetivo
Desarrollar un modelo de pronóstico del caudal diario para el embalse San Lorenzo, con un Error Porcentual Absoluto Medio (MAPE) entre el 10 % y el 15 %, que permita predecir con precisión los caudales de los próximos 2 días, con el fin de optimizar las ofertas de energía por kilovatio hora (kWh) y facilitar la implementación de una estrategia de precios más competitiva y eficiente en el mercado energético colombiano.

### Estructura de carpetas

```
Estimacion_Caudales_Jaguas
│   README.md			# Descripcion
│   
└───Modelos Finales		
│   │ 1_EDA.ipynb		# Notebook de analisis y preparación
│   │ 2_LGBM_Final.ipynb	# Entrenamiento LGBM Final
│   │ requirements.txt		# Archivo de req para 1 y 2
│
└───Otros Experimientos
│   │ 3_RandomForests.ipynb			# Experimento RF
│   │ 4_RandomForest_resample_diario.ipynb	# Experimento RF diario
│   │ 5_LSTM_univariado.ipynb			# Experimento LSTM Kaggle
│   │ 6_LSTM_multivariado.ipynb		# Experimento LSTM 2 Kaggle
│   │ 7_SARIMAX.ipynb				# Experimento SARIMAX
│
```
