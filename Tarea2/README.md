# Tarea 2 (en equipos de 4 personas máximo)

## Fecha de entrega 18 de Octubre

### Intrucciones:

a) Actualizar constatemente el repositorio de las tareas (ver Readme.md en https://github.com/MecAnalitica/curso2018)

b) Entregar notebook the Jupiter en el directorio de la tarea, con el nombre del archivo tareaX, donde X es el número de la tarea correspondiente.

c) Poner nombre del (de los) estudiante(s) como primer entrada del notebook.

d) Escribir comentarios, discusiones y conclusiones sobre el notebook.

e) Se califica redacción, organización, y presentación (nombre de ejes en las graficas, etc.).

------------------

### El péndulo forzado amortiguado

La ecuación del péndulo forzado amortiguado es 

Aceleración+Amortiguamiento+Gravedad=Fuerza externa

Que como ecuación se ve 

<img src="https://latex.codecogs.com/gif.latex?\ddot{\theta}&plus;\mu&space;\dot{\theta}&plus;\sin(\theta)=A&space;\cos&space;(w_d&space;\&space;t)" title="\ddot{\theta}+\mu \dot{\theta}+\sin(\theta)=A \cos (w_d \ t)" />,

donde hemos normalizado el tiempo para que la frencuencia natural sea 1.

1.- Límite lineal. Considerando ángulos pequeños, tenemos la ecuación lineal forzada y amortiguada vista en clase, cuya solución particular tiene una función coseno con una cierta amplitud y fase dada en términos de los parametros de la ecuación anterior. 
Tomando <img src="https://latex.codecogs.com/gif.latex?A=1\&space;\mathrm{y}\&space;\mu=0.05" title="A=1\ \mathrm{y}\ \mu=0.05" />

  a) Graficar la Amplitud como función de la frecuencia de la fuerza externa.
  
  b) Graficar la Fase de la solución como función de la frecuencia de la fuerza externa.
  
  c) Graficar el ángulo y la velocidad angular como función del tiempo.
  
  d) Graficar el espacio fase 
  
2.- 

<!-- <img src="https://latex.codecogs.com/gif.latex?T=\frac{kV&plus;g}{gk}(1-e^{-kt})" title="T=\frac{kV+g}{gk}(1-e^{-kt})" />



1.-
![figure not found](https://github.com/MecAnalitica/curso2018/blob/master/Tarea1/problem1.png)

Para el problema del misil visto en clase, encontramos una ecuación transcendental para el tiempo de vuelo.

<img src="https://latex.codecogs.com/gif.latex?T=\frac{kV&plus;g}{gk}(1-e^{-kt})" title="T=\frac{kV+g}{gk}(1-e^{-kt})" />

a) Usando algún algoritmo recursivo, crea un código que calcule T para diferentes valores de k, el ángulo y la velocidad inicial.

b) Con la velocidad inicial de 500m/s y un ángulo inicial de 65 grados, graficar el Rango contra k para (k=0, k=0.05 y otros 3 valores entre 0 y 1). Compararlo con la aproximación vista en clase basado en teoría de perturbaciones.

c) Usando los mismos datos iniciales del punto anterior, graficar Distancia Vertical contra Distancia Horizontal para k=0, y otros 4 valores entre 0 y 1.

d)Usando los mismos datos iniciales que en los puntos antioreres, graficar Altura contra Tiempo, Valocidad Horizontal contra Tiempo y Velocidad Vertical contra Tiempo para k=0, y otros 4 valores entre 0 y 1.

e)Búscar el ángulo que da la distancia máxima numéricamente para k=0, y otros 4 valores entre 0 y 1.

> Nota: el código debe ser "limpio" y tener explicaciones de como funciona cada area del mismo.



### Cálculos analíticos (subir PDF escaneado)

2.- Una escalera de longitud *L* descansa sobre una pared con una ángulo *d* con respecto a la vertical. No hay fricción entre la pared o el piso y la escalera. 

a) Escribe la energía cinética y potencial de la escalera como función de d(t). 
> *Hint: Para encontrar la velocidad del centro de masa, encuentra la longitud y altura del centro de masa como función del ángulo y luego diferencia con respecto al tiempo*

b) Usando el método de la de energía, escribe la ecuación de movimiento para d(t). Repíte el cálculo usando las leyes de Newton y compara.

c) Muestra que la escalera pierde contacto con la pared al caer cuando *3 Cos(d) = 2 Cos(do)*, donde *do* es el ángulo inicial entre la escalera y la pared en reposo. 


3.- Un tubo sólido pequeño de radio *r* se encuentra dentro de un tubo hueco más grande de radio *R*. Encuentra el periodo de las oscilaciones del tubo pequeño moviéndose dentro del grande alrededor de su punto de equilibrio. 
> *Hint: Primero muestra que la velocidad angular *w* del tubo pequeño se relaciona con el ángulo *s* que forma el vector del centro de masa del tubo grande al centro de masa del tubo pequeño y la vertical, mediante* <img src="https://latex.codecogs.com/gif.latex?w=(R-r)\dot{s}/r" title="w=(R-r)\dot{s}/r" /> -->



