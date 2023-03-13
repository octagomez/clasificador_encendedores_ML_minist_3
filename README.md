# clasificador_Encendedores_ML_minist_3

El archivo final es el ML_RED_convolucionales_TP1v3.ipynb
Se dejan los archivos ML_RED_convolucionales_TP1.ipynb y ML_RED_convolucionales_TP1v2.ipynb para observar la evolucion del codigo y del modelo.

# Instalacion en Hosting.
- Instalar en public_html los siguientes archivos:
  - 9 archivos .bin (group1-shard1of9.bin al group1-shard9of9.bin)
  - model_cnn.json 
  - index_conexion_camara.html
  
# REQUERIMIENTO

Se necesita crear un modelo de clasificacion por imagenes que clasifique en 3(Tres) marcas de encendedor. Cliper, Descartable, Bic. El modelo debera estar montado y clasificar atravez de una camara en streaming, es decir que la camara al captar con su lente alguno de estos 3 encendedores debe clasificar en CLIPER, DESCARTABLE, BIC segun corresponda.

# Funcionalidad.
Al ingresar al sitio, este solicita permiso sobre la camara web del navegador.
Al mostrar un encendedor a la camara el modelo predice que tipo de encendedor es si es un CLIPER, DESCARTABLE o BIC.

# Entrenamiento, se tomaron 100 fotos de cada encendedor y se utilizo para entrenar un modelo CNN para su clasificacion.

