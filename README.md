# 4.2-Bit-cora-de-ejercicios
De manera individual utilice python y opencv para realizar un programa que tome una imagen, puede ser el logotipo del itsva, tecnm o alguno asociado a la carrera de ingeniería en sistemas computacionales y con opencv determine el contorno o borde de la imagen.
# OpenCV

Primero se instala la libreria de Open cv :

```bash
pip install opencv-python
```

## Codigo

En las líneas 1 y 2  importamos OpenCV y numpy, en la línea 3 leemos la imagen correspondiente a la figura, luego en la línea 4 la transformamos a escala de grises, para en la línea 5 aplicar umbralización simple y así obtener una imagen binarizada.


En la línea 6 estamos usando la función cv2.findContours, en ella hemos especificado la imagen binaria, cv2.RETR_EXTERNAL, y cv2.CHAIN_APPROX_NONE, mientras que en la línea 8 tenemos la misma línea pero con 
cv2.CHAIN_APPROX_SIMPLE. 

Luego en la línea 10 dibujamos todos los contornos con cv2.drawContours. En ella especificamos la imagen en donde se van a visualizar los contornos en este caso image, los contornos corresponden a contornos1 (podríamos también especificar contornos2, pero obtendríamos la misma visualización), se dibujarán todos los contornos con -1, de color verde (0,255,0) en BGR y finalmente el grosor de línea.




## Resultado

contiene condigo que nos ayuda a realizar, encontrar y dibujar contornos de algún objeto o región de interés,

![cv2](https://user-images.githubusercontent.com/56923149/173137630-7e61fadd-8975-42eb-964b-7030582deed3.png)

### Asignatura: 
```
Inteligencia Artificial
```
### Docente:  
```
L.C.C. Jorge Manuel Pool Cen, M.M.
```
### Equipo: 
```
Miguel Ángel Cupul Osorio
Eliel David Novelo Cahum
Wilbert Jesús Del Valle Sierra
Marco Mauricio Wan Martínez
```
#### Actividad 3.3: 
```
Software Demostrativo
```
#### Fecha de entrega:  
```
sábado, 10 de junio de 2022
```
