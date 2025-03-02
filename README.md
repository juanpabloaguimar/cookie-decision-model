# Modelo de Toma de Decisiones: Toma de Galletas
Por Juan Pablo Aguilar

## Descripción
Esta aplicación web implementa un modelo interactivo para simular decisiones sobre compartir galletas, basado en factores objetivos y subjetivos. El modelo considera variables como el hambre, altruismo, altura del agente, altura del estante y el valor percibido de la galleta.

## Características
- Interfaz interactiva con controles deslizantes
- Visualización de radar para factores de decisión
- Análisis en tiempo real de la decisión
- Cálculo de esfuerzo físico basado en altura
- Interpretación de factores objetivos y subjetivos

## Instalación
1. Clonar el repositorio:
   git clone https://github.com/juanpabloaguimar/cookie-decision-model.git
   cd cookie-decision-model

2. Crear un entorno virtual:
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate

3. Instalar dependencias:
   pip install -r requirements.txt

## Uso
1. Activar el entorno virtual:
   source venv/bin/activate  # En Windows: venv\Scripts\activate

2. Ejecutar la aplicación:
   python app.py

3. Abrir en el navegador:
   http://localhost:5000

## Tecnologías Utilizadas
- Python
- Flask
- HTML/CSS
- JavaScript
- Plotly.js

## Basado en
Este modelo está inspirado en el trabajo de Jara Ettinger sobre razonamiento del comportamiento humano.
