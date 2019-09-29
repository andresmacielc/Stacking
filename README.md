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

en tu terminal de comandos y ver el panel de carga de libros de notas en tu navegador web. Intenta abrir y ejecutar el libro de example, para ver si funciona todo correctamente.
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
    
Para la instalacion del mlxtend se utiliza el siguiente comando:

    pip install mlxtend

