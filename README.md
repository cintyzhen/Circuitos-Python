# Circuitos-Python
Proyecto Final de Tópicos Especiales I (Python) - Mediante la capacidad de resolver ecuaciones de python, se resolverá circuitos RC y LR cuyos valores serán introducidos por el usuario, posteriormente se genera una gráfica que permite observar los cambios en el circuito. Se subieron a la página dos documentos, uno contiene el código y todos los archivos necesarios para ejecutar el programa desde un editor de código Python si desea verlo o editar o hacerle algún cambio y el otro es solamente el ejecutable y funciona aunque no tengas descargado Python.

## Tabla de Contenido
1. Métodos de Instalación
   - Archivos de Código  y Ejecución del Programa
   - Archivo Ejecutable
2. Uso
3. Resultados
4. Créditos

## Métodos de Instalación

### Archivos de Código  y Ejecución del Programa

 1. Librerias Necesarias 
Para instalar el proyecto y que este ejecute de manera local es neceario tener las siguientes librerias instaladas en su python. Y para una mejor ejecución de la misma, se recomiendan las siguientes versiones. Con versiones posteriores o anteriores no se asegura el buen funcionamiento del programa.
       • NumPy  (1.17)
       • SciPy (1.3.0)
       • Matplotlib (Versión usable - 1.51 hasta 3.03)
       • wxPython (4.0.7)
       • Tornado (6.0.3)
Nota: Para descargar o actualizar las librerias utilice el comando "pip install <Nombre de la libreria>". En caso de no tener pip en su python, siga las instrucciones siguientes : [Instalar Pip en Windows](https://www.liquidweb.com/kb/install-pip-windows/).
Nota #2: Es necesario definir el módulo Backend que usaría el la librería matplotlib ya que en algunos casos no se mostraban las gráficas. Se utilizó WxAgg 
 > matplotlib.use('WXAgg')

### Ejecutable

Tras descargar el archivo, descomprimalo y siga las siguientes instrucciones.
1. Ingrese a la carpeta dist
2. Ingrese a la carpeta Circuitos
3. Busque el archivo ejecutable (.exe) llamado Circuitos. - Circuitos.exe
4. Se ejecutará el programa y siga los pasos de la sección Uso, o pruebe como prefiera.

## Uso
Al instalar y correr el programa, podrá observar que se genera una ventana con dos pestañas, cada una representa un circuito diferente. Los circuitos mostrados son los circuitos RC y RL para cada circuito los valores ingresados son diferentes. A continuación se explicaran brevemente los campos a ingresar.

   • Circuitos LR: En este circuito el usuario necesita introducir los valores de los componentens del circuito en este caso son: voltaje, la resistencia, así como el inductor. Además para poder ejecutar bien los calculos necesarios para el desarrollo del problema se pide los parámetros iniciales como lo es la corriente evaluado en cero, y el cambio en el tiempo (dt), además del límite superior de la gráfica, y lo más importante el tiempo en donde desea evaluar el circuito.
   
   • Circuitos RC: En este circuito el usuario necesita introducir los valores de los componentes del circuito en este caso: voltaje, la resistencia, así como el inductor. Además para poder ejecutar bien los calculos necesarios para el desarrollo del problema se pide los parámetros iniciales como lo es el voltaje evaluado en cero, y el cambio en el tiempo (dt), además del límite superior de la gráfica.


## Resultados Obtenidos
Para el circuito RL se generará el valor de la corriente tras pasar el tiempo ingresado por el usuario, además saldrá una nueva pantalla donde podrá observar el comportamiento de la corriente en el circuito. 
Para el circuito RC se generará el valor del voltaje tras pasar el tiempo ingresado por el usuario, además saldrá una nueva pantalla donde podrá observar el comportamiento del voltaje en el circuito. 

## Créditos
Autores del Proyecto:
  • Adeel Gajia       adeel.gajia@utp.ac.pa
  • Jeremías Herrera  jeremias.herrera1@utp.ac.pa
  • Cinty Zhen        cinty.zhen@utp.ac.pa
  
*Queremos hacer en esta sección un agradecimiento al profesor Javier Sanchez Galán, por su guía y por responder todas las dudas que se tenía con respecto a los diversos temas del trabajo. *
