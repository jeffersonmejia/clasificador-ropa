# Clasificador Fashion MNIST

## 1. Resumen

Aplicacion web simple que permite dibujar o subir una imagen de una prenda y clasificarla con un modelo de TensorFlow.js.

No requiere backend. El modelo se carga desde la carpeta local `tfjs_target_dir`.

## 2. Dataset usado

Se uso el dataset Fashion MNIST, que contiene imagenes en escala de grises de 10 tipos de prendas:

`T-shirt/top`, `Trouser`, `Pullover`, `Dress`, `Coat`, `Sandal`, `Shirt`, `Sneaker`, `Bag`, `Ankle boot`.

## 3. Instalacion

No hay dependencias que instalar para ejecutar la pagina.

Para correrla, abrir `index.html` con Live Server desde la carpeta raiz del proyecto.

Tambien se puede ejecutar por terminal:

```bash
python3 -m http.server 8000
```

Luego abrir:

```text
http://localhost:8000
```
