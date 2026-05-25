## Tabla de Frecuencias y Análisis Estadistico

![alt text](image-1.png)

---

Con base en la tabla de distribución de frecuencias, el histograma, el polígono de frecuencias y la ojiva, se pueden realizar varios análisis estadísticos importantes:

1. Análisis general de los datos

Los datos tienen las siguientes características:

Número de datos: 30
Valor mínimo: 35
Valor máximo: 76
Rango: 41
Número de clases: aproximadamente 6
Tamaño de clase: aproximadamente 7

Esto indica que los datos fueron agrupados correctamente en intervalos para facilitar su interpretación.

2. Clase con mayor frecuencia (Moda)

La clase con mayor frecuencia es:

| Intervalo | Frecuencia |
| --------- | ---------- |
| 42 – 49   | 9          |

Esto significa que la mayor concentración de datos está entre 42 y 49.

La distribución presenta una tendencia central en ese intervalo, por lo que podría considerarse la clase modal.

3. Comportamiento del histograma

El histograma muestra que:

Las frecuencias aumentan desde la primera clase hasta la segunda.
Luego comienzan a disminuir gradualmente.
Existe una cola hacia la derecha.

Esto sugiere una distribución:

ligeramente asimétrica positiva,
con concentración en valores medios,
y pocos valores altos.

Visualmente no parece una distribución uniforme.

4. Interpretación del polígono de frecuencias

El polígono permite observar la tendencia de los datos:

El punto máximo ocurre en la marca de clase 45,5.
Después de ese punto las frecuencias disminuyen.

Esto confirma que:

la mayor parte de los datos está en valores medios,
y existen menos observaciones en los extremos.

5. Interpretación de la ojiva

La ojiva representa la frecuencia acumulada.

Se puede concluir:

Hasta el intervalo 42–49 ya se acumula el 46,67% de los datos (14 datos).
Hasta 56–63 se acumula aproximadamente el 86,67%.
Los valores superiores a 70 son muy pocos.

La ojiva también permite estimar:

mediana,
percentiles,
cuartiles.

6. Concentración porcentual

Según la frecuencia relativa porcentual:

| Intervalo | FR%    |
| --------- | ------ |
| 35 – 42   | 16,67% |
| 42 – 49   | 30,00% |
| 49 – 56   | 23,33% |
| 56 – 63   | 16,67% |
| 63 – 70   | 10,00% |
| 70 – 77   | 3,33%  |

Se observa que:

Más del 53% de los datos están entre 42 y 56.
Solo el 3,33% está entre 70 y 77.

7. Posibles medidas estadísticas

A partir de la tabla se podrían calcular:

Media aproximada

Usando marcas de clase:

![alt text](image.png)

Mediana

La mediana estaría aproximadamente en la clase:

49−56

porque allí se supera la mitad de los datos acumulados.


Moda

La moda corresponde aproximadamente a:

42−49

por ser la clase de mayor frecuencia.

8. Conclusión general

Los datos presentan:

concentración en valores intermedios,
pocos valores extremos,
una distribución ligeramente sesgada hacia la derecha,
y un comportamiento relativamente estable.

La mayoría de observaciones se encuentra entre:

42 y 63

lo cual representa el núcleo principal de la distribución.

---
## Como se puede determinar el número de clases en excel de acuerdo con el ejercicio?

El número de clases en una distribución de frecuencias normalmente se determina usando la Regla de Sturges, que es la que parece utilizarse en tu ejercicio.

La fórmula es:

k=1+3.322log
10
	​

(n)

Donde:

k = número de clases
n = número total de datos

En tu ejercicio:

n=30

Entonces:

k=1+3.322log
10
	​

(30)

Calculando:

log
10
	​

(30)≈1.4771

Entonces:

k=1+(3.322)(1.4771)
k≈1+4.907
k≈5.907

Se aproxima a:

k≈6 clases

Por eso en la tabla aparecen 6 intervalos de clase.

Cómo hacerlo en Excel

La fórmula en Excel sería: 
 
</> excel
=1+3,322*LOG10(A1)