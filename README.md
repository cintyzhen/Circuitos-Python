# Circuitos-Python
Proyecto Final de Tópicos Especiales I (Python) - Mediante la capacidad de resolver ecuaciones de python, se resolverá circuitos RC y LR cuyos valores serán introducidos por el usuario, posteriormente se genera una gráfica que permite observar los cambios en el circuito. 

-----Tabla de Contenido-------



-----Instalación-----

 •Librerias Necesarias
   Para instalar el proyecto y que este ejecute de manera local es neceario tener las
   siguientes librerias instaladas en su python
       • NumPy 
       • SciPy
       • Matplotlib (Versión superior a 1.5)
       • wxPython 
Nota: Para descargar o actualizar las librerias utilice el comando "pip install <Nombre de la libreria>". En caso de no tener pip en su python, siga las instrucciones siguientes : "https://www.liquidweb.com/kb/install-pip-windows/"



------Uso------
Al instalar y correr el programa, podrá observar que se genera una vetana con dos pestañas, cada una representa un circuito diferente. Los circuitos mostrados son los circuitos RC y RL para cada circuito los valores ingresados son diferentes. A continuación se explicaran brevemente los campos a ingresar.

   • Circuitos LR: En este circuito el usuario necesita introducir los valores de los componentens del circuito en este caso son: voltaje, la resistencia, así como el inductor. Además para poder ejecutar bien los calculos necesarios para el desarrollo del problema se pide los parámetros iniciales como lo es la corriente evaluado en cero, y el cambio en el tiempo (dt), además del límite superior de la gráfica, y lo más importante el tiempo en donde desea evaluar el circuito.
   
   • Circuitos RC: En este circuito el usuario necesita introducir los valores de los componentes del circuito en este caso: voltaje, la resistencia, así como el inductor. Además para poder ejecutar bien los calculos necesarios para el desarrollo del problema se pide los parámetros iniciales como lo es el voltaje evaluado en cero, y el cambio en el tiempo (dt), además del límite superior de la gráfica.


----Resultados----
Para el circuito RL se generará el valor de la corriente tras pasar el tiempo ingresado por el usuario, además saldrá una nueva pantalla donde podrá observar el comportamiento de la corriente en el circuito. 
Para el circuito RC se generará el valor del voltaje tras pasar el tiempo ingresado por el usuario, además saldrá una nueva pantalla donde podrá observar el comportamiento del voltaje en el circuito. 

-----Créditos------
Autores del Proyecto: 
  • Adeel Gajia       adeel.gajia@utp.ac.pa
  • Jeremías Herrera  jeremias.herrera1@utp.ac.pa
  • Cinty Zhen        cinty.zhen@utp.ac.pa
