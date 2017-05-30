# Population vs Profit
## Descripcion
Este dataset es un ejercicio del curso de Machine Learning de Andrew Ng. Consiste en un conjuto de datos de 2 variables:
* Poblacion de una ciudad
* Ganancias (profit) de un restaurante en dicha ciudad



![alt text][s1]

Este dataset tiene 97 muestras.


### Formato Datos
Los datos se encuentran en el archivo `data.csv`.

### Variables
El archivo csv no tiene headers. Las columnas son las siguientes:
1. Tamaño de la Poblacion
2. Ventas (profit)


### Objetivo
Construir un algoritmo de regression que prediga las ganancias de un local dada la poblacion de la ciudad en la que se encuentra.

### Notas Teoricas
* [Regresion Lineal](https://es.wikipedia.org/wiki/Regresi%C3%B3n_lineal)

### Solucion
Ver procedimiento de [solucion](https://github.com/colomb-ia/formato-retos#solucion).

##### Requerimientos
*Indica los requerimientos para utilizar el codigo de tu solucion.*

##### Procedimiento
*Indica el procedimiento que se debe seguir para reproducir tu solucion.*

##### Metodo
*Indica el metodo que utilizaste para solucionar el reto.*

##### Resultados
*Indica el metodo que utilizaste para solucionar el reto.*

## Getting Started
Para resolver este reto primero has un [fork](https://help.github.com/articles/fork-a-repo/) de este repositorio y [clona](https://help.github.com/articles/cloning-a-repository/) el fork en tu maquina.

```bash
git clone https://github.com/{username}/supervised-basico-population-vs-profit-1d
cd supervised-basico-population-vs-profit-1d
```

*Nota: reemplaza `{username}` con tu nombre de usuario de Github.*

### Requerimientos
Para descargar y visualizar los datos necesitas Python 2 o 3. Las dependencias las puedes encontrar en el archivo `requirements.txt`. Puedes instalarlas fácilmente utilizando el commando

```bash
pip install -r requirements.txt
```
Dependiendo de tu entorno puede que necesites instalar paquetes del sistema adicionales, si tienes problemas revisa la documentación de estas librerías.

# Starter Code Python
Para iniciar con este reto puedes correr el codigo de Python en Jupyter del archivo `python-sample.ipynb`. Este código que ayudará a cargar y visualizar algunas imágenes. Las dependencias son las mismas que se instalaron durante la descarga de los datos, ver [Requerimientos](#requerimientos).

Para iniciar el código solo hay que prender Jupyter en esta carpeta

```bash
jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10 .
```
y abrir el archivo `python-sample.ipynb`.


[s1]: images/graph.png "S"
