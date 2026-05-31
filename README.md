# Mercado Justo — Predicción de Precios del Café

Análisis y pronóstico de precios para apoyar decisiones de comercialización
de pequeños productores de café en Chiapas, Oaxaca y Veracruz.

## Links

- [Documentación completa (GitBook)](https://davids-5.gitbook.io/mercado-justo-cafe/)
- [Bot de Telegram](https://t.me/mercadojusto_cafe_bot)

## Stack tecnológico

PySpark · ARIMA · Random Forest · PuLP · Plotly · Telegram Bot · Yahoo Finance API

## Estructura

- `notebook/` — Notebook principal (.ipynb)
- `bot/` — Bot de Telegram (Python)
- `bot_data/` — Modelos y datos exportados
- `dataset/` — DataSet del SIAP
- `graficas/` — Gráficas del análisis
- `qr_codes/` — Códigos QR de los sitios

## Cómo ejecutar

### Notebook
1. Abrir `notebook/Mercado_Justo_Cafe_Final.ipynb` en Jupyter
2. Abrir link de google colab (https://colab.research.google.com/drive/1-I11K8-_SGjHxH1O4DCqwfYiSJq09LZD?usp=sharing)
3. Subir `cafe_cereza_2003_2024.xlsx` al entorno
4. Ejecutar todas las celdas

### Bot de Telegram
1. `cd bot/`
2. `cp config.py.example config.py` y agregar tu token
3. `bash setup.sh`
4. `source venv/bin/activate && python3 bot.py`

## Equipo

David Pitol Arana, 
Daniela Hernandez Carrada, 
Rene De la Cruz Escobar, 
Daniel Aldair Montiel Macias

Universidad Nacional Rosario Castellanos
Licenciatura en Ciencias de Datos para Negocios — 5° Semestre — 2026