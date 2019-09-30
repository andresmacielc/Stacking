# Stacking

# Notas de instalación

Para la correcta ejecucion se requiere tener instalaciones lo más recientes posibles de:

    NumPy
    SciPy
    matplotlib
    pandas
    pillow
    scikit-learn
    IPython
    mlxtend
    Jupyter Notebook
    
    
  Este último es importante. Si lo tienes correctamente instalado, deberías poder teclear:

    jupyter notebook

en tu terminal de comandos y ver el panel de carga de libros de notas en tu navegador web. Intenta abrir y ejecutar el libro de ensamble para ver si funciona todo correctamente.
Para aquellos usuarios que no tengan las dependencias instaladas, una forma relativamente sencilla de conseguirlas es utilizar una distribución de Python como Anaconda CE, que incluye los paquetes de Python más relevantes para ciencia, matemáticas, ingeniería y análisis de datos.
Suponiendo que tengas Anaconda instalado, los siguientes comandos crean un entorno nuevo llamado sklearn-env e instalan todas las dependencias:

    conda update conda
    conda update anaconda
    conda create --prefix ~/sklearn-env scikit-learn
    source activate sklearn-env
    conda install matplotlib
    conda install ipython
    conda install pandas
    conda install Pillow
    
Para la instalación del mlxtend se utiliza el siguiente comando:

    pip install mlxtend


Si no estás familiarizado con GitHub o no tienes cuenta, también puedes bajar todo el repositorio como un archivo .zip, accediendo a Clone or download en la cabecera del repositorio (https://github.com/andresmacielc/Stacking) y pulsando sobre Download ZIP

![alt text](https://raw.githubusercontent.com/andresmacielc/Stacking/blob/master/Images/repo.png)

Una vez dentro del libro, ejecuta todas las celdas de código a la vez pulsando sobre el botón "Run All", tal y como muestra esta figura:


![alt text](https://raw.githubusercontent.com/andresmacielc/Stacking/blob/master/Images/img_ens.png)

De estar todo correcto, el contenido podra ejecutarse en su totalidad.

Aunque no sea un requisito, te recomendamos actualizar los paquetes Python a su ultima versión, para así asegurar la mejor compatibilidad con el código. Puedes actualizar los paquetes con los comandos:

    pip install [package-name] --upgrade
