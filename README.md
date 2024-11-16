El siguiente repositorio muestra un ejemplo básico para la conexión del ESP32 con la nube de arduino IoT.

Se conectó un potenciometro a una entrada analogica para visualizar una gráfica en la nube del voltaje

Los pasos a seguir son los siguientes: 

  1) crear una cuenta en arduino e ingresar en arduino cloud
  2) Crea un nuevo dispostitivo (things)
  3) Después en asociar dispositivo seleccionamos la placa con la que estemos trabajando ya sea arduino o algun modulo ESP32
  4) Descargamos el pdf o copiamos la clave secreta
  5) vamos a network configure y ponemos el nombre y la contraseña de la red wi-fi a la que nos vayamos a conectar y pegamos la clave secreta
  6) Creamos una nueva variable, la cual mostraremos en nuestro dashboard
  7) creamos un nuevo dashboard y creamos un widget grafico y lo enlazamos con la variable creada
  8) en la sección sketch podremos encontrar el IDE de arduino, copiamos el contenido que esta en el directorio main (main.ino)
  9) Descargamos un software para poder cargar los codigos de arduino cloud. Buscamos arduino cloud create agent download e ingresamos al primer enlace y descargamos el archivo
  10) Una vez descargado el agente, en el ardduino cloud nos deveria reconocer el puerto COM y podremos cargar el codigo
  11) Con esto podremos visualizar los datos de voltaje de un potenciometro en la grafica (como se muestra en Grafica.png)
