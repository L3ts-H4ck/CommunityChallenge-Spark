# Mírame mamá soy una pintura 🍏

## 1) Encuentra recursos.

### - Busque la inspiración adecuada para sus filtros, deje volar su imaginación

## 2) Abra Spark AR y cree un nuevo proyecto.

### - Una vez que abramos el programa Spark AR, seleccionaremos ```New Project```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_1.jpg?raw=true" width="50%">

## 3) Agrega un Face Tracker

### - Lo primero que necesitamos es un objeto nuevo, así que haremos clic en ```Add object```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_2.jpg?raw=true" width="50%">

### - Necesitamos un lienzo, y dentro del lienzo 2 rectángulos

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_3.jpg?raw=true" width="50%">

### - Cambiaremos el nombre de los rectángulos a ```user``` y ```bg```, también asegúrese de que en el material ha seleccionado el objeto 3D.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_5.jpg?raw=true" width="50%">

### - En estas mismas propiedades, asegúrese de tener la opción marcada  ```visible``` y la ```position``` en ```Fill Height``` .

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_7.jpg?raw=true" width="50%">

### - Ahora iremos a la cámara, una vez seleccionada, podemos cambiar sus propiedades.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_8.jpg?raw=true" width="50%">

### - En ```texture``` elegiremos ```cameraTexture0``` y en  ```Segmentation``` => ```Person```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_9.jpg?raw=true" width="50%">

### - Para el rectángulo ``user``, agregaremos un nuevo ``material``. Llámado ``user`` y cambia sus propiedades: 
- ``Shader Type`` => ``Flat``
- ``STexture`` => ``CameraTexture0``
- ``Alpha`` => Checked

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_10.jpg?raw=true" width="50%">

### - Una vez que tenemos la opciónel ``Alpha`` seleccionada, elegimos la textura que queremos, en este caso seleccionaremos ``personSegmentationMaskTexture0``

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_11.jpg?raw=true" width="50%">

### - La pantalla tiene que verse así.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_12.jpg?raw=true" width="50%">

### - Ahora es el turno del otro rectángulo, agregaremos un material nuevo.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_13.jpg?raw=true" width="50%">

### - Para este material, creamos una nueva textura. Seleccionaremos ahora el fondo que queremos.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_14.jpg?raw=true" width="50%">

### - Una vez hecho esto, podemos ver el fondo de nuestra pintura.. 

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_15.jpg?raw=true" width="50%">

## 4) Agregue los elementos 3D dentro del rastreador facial.

### - Lo siguiente es agregar el ``Face Tracker`` para nuestro filtro.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_16.jpg?raw=true" width="50%">

### - Esta es la parte divertida, comenzaremos a agregar nuestros activos.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_17.jpg?raw=true" width="50%">

### - Seleccionamos ``import from computer``

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_18.jpg?raw=true" width="50%">

### - Para ello hemos preparado nuestros propios activos, puedes hacerlo tú, o simplemente usar los que estamos usando.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_19.jpg?raw=true" width="50%">

### - En los archivos que acabamos de cargar, hay uno que contiene la cabeza de nuestra máscara.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_20.jpg?raw=true" width="50%">

### - Necesitamos arrastrarlo a nuestro ``Face Tracker`` para que podamos usarlo.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_21.jpg?raw=true" width="50%">

### - Repetimos este mismo proceso para el sombrero.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_22.jpg?raw=true" width="50%">

### - Ahora tenemos una cabeza con un sombrerito.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_23.jpg?raw=true" width="50%">

### - Y una vez más, pero ahora con la manzana

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_24.jpg?raw=true" width="50%">

## 5) Arreglar los elementos 3d

### - Moviremos la manzana y todos los demás elementos al lugar que queramos, puedes hacerlo con la herramienta de selección en la parte superior de la pantalla.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_25.jpg?raw=true" width="50%">

## 6) Preparar y probar

### - Ahora tenemos todos los activos que necesitamos, solo tenemos que cambiar sus colores, para eso necesitamos cambiar el ``Blend Mode`` => ``Replace`` y el ``Opacity`` => 100%

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_26.jpg?raw=true" width="50%">

### - En la sección superior podemos cambiar el color de los elementos.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_27.jpg?raw=true" width="50%">

### - Una vez hecho, lo único que queda por hacer es probarlo y enviarlo a revisión.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_28.jpg?raw=true" width="50%">



