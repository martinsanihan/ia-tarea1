# Tarea 1 Inteligencia Artificial

Este es un repositorio complementario para la tarea 1 de Inteligencia Artificial. Su uso es solo en caso de tener algún problema con el archivo `.ipynb` original que se entregó en Canvas.

## Requisitos Previos

- Python 3.12
- Git

## Archivos importantes

- `fernando_ortega_ihan_sanmartin_Tarea1.ipynb`: notebook principal de la tarea.
- `aerolinea_limpio.csv`: dataset usado en la Actividad 1.
- `energydata_complete.csv`: dataset usado en la Actividad 2.
- `requirements.txt`: librerías necesarias para ejecutar el notebook, incluyendo `pgmpy` y `hmmlearn`.

## Paso a paso

**1. Clonar Repo**

`git clone https://github.com/martinsanihan/ia-tarea1`

**2. Crear y activar el ambiente virtual**

Para poder aislar las dependencias y ejecutar el código, se debe crear un ambiente virtual. En la terminal, posicionado en el directorio del repositorio, ejecuta:

`python3 -m venv .venv`

Luego, activa el ambiente virtual:

`source .venv/bin/activate`

**3. Instalar dependencias**

Una vez activado el ambiente virtual (verás un prefijo `(.venv)` en tu terminal), instala todas las librerías necesarias ejecutando obligatoriamente:

`pip install -r requirements.txt`

**4. Iniciar Jupyter Notebook**

Finalmente, ejecuta el siguiente comando para abrir la interfaz en tu navegador y poder acceder al archivo `.ipynb`:

`jupyter notebook`

Una vez abierto el notebook, se recomienda ejecutar todo desde cero usando:

`Kernel -> Restart Kernel and Run All Cells`

Así se verifica que todas las celdas corran en orden y que las variables necesarias para cada actividad queden cargadas correctamente.
