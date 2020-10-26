# En el mundo de VanGogh <img src="https://www.enlinealasalle.com/pluginfile.php/8983/course/overviewfiles/vincent-van-gogh-png-2.png" height="25">

# Hacer el fondo

### - Lo primero que debemos hacer es abrir Spark AR y crear un nuevo proyecto.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/01.png?raw=true" width="50%">

### - Una vez cargada la interfaz, daremos clic en la opción "Add Object".

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/03.png?raw=true" width="50%">

### - Necesitamos buscar la opción "lienzo" y hacer clic en ella. Un lienzo es una capa donde podemos agregar otros elementos, estos elementos pueden ser dinámicos o estáticos.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/04.png?raw=true" width="50%">

### - Una vez agregamos esto a nuestro lienzo, seleccionamos nuevamente la opción "Agregar objeto" y agregamos un rectángulo

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/05.png?raw=true" width="50%">

### - Ahora podemos ver el rectángulo en el lienzo.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/06.png?raw=true" width="50%">

### - Necesitamos agregar otro rectángulo, el primero es para el usuario y el segundo es para el fondo.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/07.png?raw=true" width="50%">

### - Una vez que cambiamos los nombres de los rectángulos a ```user``` y ```bg```, podemos proceder a editarlas.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/08.png?raw=true" width="50%">

### - Si seleccionamos el rectángulo, podemos editar sus propiedades en el lado derecho.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/09.png?raw=true" width="50%">

### - Necesitamos cambiar su ancho y alto al 100%. Esto nos asegura que cubramos el orificio de la pantalla y no dejemos ningún espacio en blanco en el filtro.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/10.png?raw=true" width="50%">

### - Una vez que tenga las propiedades como nosotros, ahora tenemos que agregar un material al rectángulo de usuario. Hacemos clic en el signo más en la sección de material.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/11.png?raw=true" width="50%">

### - Cambiemos el nombre del material a ```user ```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/12.png?raw=true" width="50%">

# Agregar texturas y segmentación de la cámara

### - En la parte superior de los rectángulos, está la sección de la cámara. Necesitamos hacer clic en él porque ahora necesitamos agregar la textura y la segmentación.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/13.png?raw=true" width="50%">

### - En el lado derecho podemos encontrar las propiedades de la cámara.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/14.png?raw=true" width="50%">

### - Vamos a hacer clic en ```Texture Extraction``` y seleccionamos ```cameraTexture0```, a continuación, en Segmentación, seleccionaremos el ```personSegmentationMaskTexture0``` .

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/15.png?raw=true" width="50%">

# Vista previa de nuestro Vangogh BG

### - Ahora en las propiedades del material en ```Shader Type``` seleccionamos ```Flat``` .

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/16.png?raw=true" width="50%">

### - En ```Texture``` seleccionamos ```cameraTexture0```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/17.png?raw=true" width="50%">

### - Una vez que hayamos hecho eso, en  ```Alpha``` seleccionamos la casilla. 

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/18.png?raw=true" width="50%">

### - En ```Texture``` seleccionamos ```personSegmentationMaskTexture0```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/19.png?raw=true" width="50%">

### - Necesitamos agregar el lienzo del usuario en otra capa, esto porque queremos que estén separados, el usuario del fondo.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/20.png?raw=true" width="50%">

### - Si ha hecho todo hasta ahora de acuerdo con el tutorial, verá algo como esto. Tenemos a nuestro usuario separado del fondo en diferentes capas.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/21.png?raw=true" width="50%">

### - Ahora necesitamos un material para nuestros antecedentes..

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/22.png?raw=true" width="50%">

### - Cambiemos su nombre a ```bg```.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/23.png?raw=true" width="50%">

### - El fondo necesita una nueva textura, ahora es el momento de seleccionar la imagen que teníamos para nuestro fondo y agregarla al proyecto.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/24.png?raw=true" width="50%">

### - Como puedes ver, ahora tenemos nuestro fondo hecho. Lo siguiente es hacer la corona.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/25.png?raw=true" width="50%">

# Hacer la corona

### - Lo primero que debe hacer para hacer la corona es agregar un ```Face Tracker``` localizado en ```Add Object```.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/26.png?raw=true" width="50%">

### - Y dentro del ```Face Tracker```, vamos a agregar un nuevo objeto, en este caso un ```Plane```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/27.png?raw=true" width="50%">

### - Si miras de cerca, ahora tenemos un rectángulo siguiendo el rostro de la persona. Pero está fuera de lugar, solo tenemos que moverlo un poco hacia adelante.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/28.png?raw=true" width="50%">

### - Ahora vamos al fondo de la sección ```Textures``` , y agregue todas las imágenes para nuestra corona.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/29.png?raw=true" width="50%">

### - En este caso agregamos 3 imágenes, tienen que estar al mismo nivel de las otras texturas.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/30.png?raw=true" width="50%">

### - Por cada imagen que agregue, debe agregar al menos una ```Plane``` sobre el ```Face Tracker```, en cada plano habrá una imagen, pero puedes tener tantos planos como quieras, si quieres repetir la misma imagen una y otra vez.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/31.png?raw=true" width="50%">

### - Ahora en la sección superior, hay un ícono con cuatro flechas, una vez que seleccionamos este ícono, podemos mover todos los planos que hemos creado.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/32.png?raw=true" width="50%">

### - Una vez que hayamos colocado todos los planos, les agregamos los materiales.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/33.png?raw=true" width="50%">

### - Llamémoslos igual que los archivos.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/34.png?raw=true" width="50%">

### - Ahora elegimos la textura, esa va a ser la imagen que tenemos.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/35.png?raw=true" width="50%">

### - Lo que pasó aquí es que este avión está detrás de los demás.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/36.png?raw=true" width="50%">

### - Solo necesita reorganizarlos como le parezca en forma.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/37.png?raw=true" width="50%">

# Acabados finales

### - Si no desea que su filtro se vea así, podemos solucionarlo.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/38.png?raw=true" width="50%">

### - Crea una nueva capa.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/39.png?raw=true" width="50%">

### -  Y agregue más imágenes a esta capa.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/40.png?raw=true" width="50%">

 ### - Luego, muévelo a los lados de la cara para que luzca más natural.
 
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/41.png?raw=true" width="50%">


# El resultado

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/42.png?raw=true" width="50%">
