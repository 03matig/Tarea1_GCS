# Tarea 1 - Gestión de Cadena de Suministros

Este repositorio contendrá el programa de Gurobi utilizado para desarrollar lo solicitado en los incisos b (resolución del modelo) y c (gráfico de la solución obtenida) para los problemas 1 y 2 de la tarea encomendada por el profesor Rodrigo Ortúzar en horario de clase, con fecha límite de entrega el día Jueves 25 de Septiembre de 2025 a las 23:59.

## Integrantes:

Los integrantes somos:
1. Joaquín Romero Jirón
2. Matías Garín Avendaño

## ¡Aviso!

Los archivos oficiales a entregar son:
1. Tarea1_Problema1.ipynb
2. Tarea1_Problema2.ipynb

¡Muchas gracias!

## Instrucciones para compilar
1. Clonamos el repositorio
```
git clone https://github.com/03matig/Tarea1_GCS.git
```
2. Instalamos el paquete que permite crear entornos virtuales
```
pip install virtualenv
```
3. Levantamos nuestro entorno virtual
```
virtualenv .venv
```
4. Luego, ingresamos al entorno virtual de la manera que tu sistema operativo lo reconozca. Después de eso, instalamos nuestras dependencias:

```
pip install -r requirements.txt
```
5. En los archivos de Jupyter Notebook se debe seleccionar el Kernel de Python que apunta hacia el entorno virtual levantado. Una vez hecho esto, si se desea compilar el código nuevamente en comparación al output que ya está arrojado, entonces se puede hacer libremente ya que las dependencias se encuentran instaladas.


## Estructura del proyecto
```
📁 Tarea1_GCS/
├── Tarea1_Problema1.ipynb  ← Notebook principal con todo el código y visualizaciones para el problema 1
├── Tarea1_Problema2.ipynb ← Notebook principal con todo el código y visualizaciones para el problema 2
├── data/
│   ├── generador_instancias.py  ← Script que genera coordenadas y parámetros con seed reproducible
│   └── instancias/              ← Carpeta para guardar instancias generadas (.csv o .npy)
└── requirements.txt            ← Lista de paquetes a instalar