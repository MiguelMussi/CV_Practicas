# TUIA - Visión por Computadora

## Ejercicios Unidad 1

1. Elija una de las imágenes color que tomó para la clase y aplique separación de canales y elija un método para transformarla en escala de grises. Muestre por pantalla los resultados obtenidos. 
2. Con las fotografías pedidas por la cátedra la clase pasada (la foto de objetos con fondo liso, y fotos del mismo producto en un contexto más complejo) usar los métodos de extracción de características (esos anteriores al Deep Learning) para encontrar la ubicación del producto dentro de la imagen. 
3. Para leer un paper, conviene arrancar leyendo el abstract, luego hacer una lectura por los títulos de las distintas secciones, prestar atención a las imágenes y su texto asociado, y leer con detalle la conclusión. 
    
    Se dividirá la comisión completa en 5 grupos de dialogo, cada grupo tomará un paper diferente de los que se muestran en la sección “Técnicas de extracción de características mediante aprendizaje profundo.” Les proponemos hacer una primera lectura del mismo. Luego de la misma un par de valientes del grupo dará una breve presentación de los mismos.
    
    [01_superpoint.pdf](https://drive.google.com/file/d/1tx6GrL1Cr-LnQBSH1K9xffPxbasQugE9/view?usp=drive_web)
    
    [02_d2net.pdf](https://drive.google.com/file/d/1-b07QhWcRdQWYhZxQ6wY97KN_Oiu1M8L/view?usp=drive_web)
    
    [03_NeurIPS.pdf](https://drive.google.com/file/d/1su2irZiTg1brgTUaAGxgUquHzZDzp_7d/view?usp=drive_web)
    
    [04_liu2018.pdf](https://drive.google.com/file/d/1IQT7nKAHXQD7opxk7ws-mLok7NGdXe09/view?usp=drive_web)
    
    [05_Zhang_Deep_Graphical_Feature_Learning.pdf](https://drive.google.com/file/d/15mFrmQvKmCFX_WeFNYfticSOrOKcKVTL/view?usp=drive_web)
    
4. Con los videos de [youtube.com](http://youtube.com) de cámara fija pedidos para esta clase, aplicar los algoritmos de detección de movimiento vistos en la teoría.
5. (Entrega obligatoria individual en repo) Genere un video en un patio o en un hall de edificio donde en un principio se vea vacío y luego aparezca una persona. Mediante los métodos de motion detection (sin usar deep learning) logre una detección de la persona cuando entra al cuadro suponiendo la utilidad para una cámara de seguridad. 
Luego sobre el mismo video aplique los algoritmos de flujo denso y disperso que se mostraron en clase. 
Escriba una reflexión sobre los resultados en el formato md dentro del Jupyter Notebook.
6. (Entrega obligatoria individual en repo) Explique cuál es diferencia entre localización de objetos y clasificación de imágenes. Muestre ejemplos de ello.
7. Continuando con el ejercicio 3, de lectura de papers, les proponemos hacer una primera lectura de los siguientes papers. Luego de la misma otro par de valientes del grupo dará una breve presentación de los mismos. En total a cada grupo le tocará leer dos papers uno de cada ejercicio.
    1. **[LeNet-5](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)**  (quienes tomaron el 1 del ejercicio 3)
    2. **[VGGNet](https://arxiv.org/abs/1409.1556)**  (quienes tomaron el 2 del ejercicio 3)
    3. **[GoogLeNet](https://arxiv.org/abs/1409.4842)**  (quienes tomaron el 3 del ejercicio 3)
    4. **[ResNet](https://arxiv.org/abs/1512.03385)**  (quienes tomaron el 4 del ejercicio 3)
    5. **[Transformers in Vision](https://arxiv.org/abs/2010.11929)**   (quienes tomaron el 5 del ejercicio 3)
8. (Entrega obligatoria individual en repo) En lo posible, realizar videos donde una clase de objeto difiera en número con otros objetos (sino, utilizar videos bajados de internet). Por ejemplo, al aire libre, un perro que se mueva entre personas en un parque. Una persona en bicicleta entre muchos autos en una calle de la ciudad. Luego, utilizar los distintos algoritmos presentados en teoría para detectar solo la clase minoritaria con su respectiva etiqueta. Indicando en cada caso la herramienta utilizada y comparando los niveles de confianza de detección logrados. 
9. (Entrega obligatoria individual en repo) Tomar fotografías donde coexistan varios objetos en posiciones solapadas y no, en contextos de diferente complejidad. Luego, aplicar los algoritmos de segmentación propuestos y verificar los resultados de cada uno. Comentar qué diferencias observa. 
10. Con el mismo video usado en el ejercicio 4, realice un seguimiento de objetos con el código propuesto en la sección de ejemplos prácticos.
11. Tome fotos donde se vea su rostro y el de varias personas. Asegúrese de tener fotos que tengan uno, dos y más caras diferentes. Implemente la librería OpenCV para la detección de rostros en ambos casos. Analice paso a paso el código que permite la detección de elementos de un rostro. 
12. Tome fotos donde sólo se vea un rostro (suyo o de otras personas) desde distintos ángulos y en distintas posturas. Luego, utilizando la librería DeepFace verifique, comparando dichas fotos, si los rostros corresponden a la misma persona o no. 
13. Experimente creando un programa que reemplace caras por un emoji que corresponda a la expresión de la cara en cuestión.  Analice si puede realizarlo en tiempo real.


## Ejercicios Unidad 2
