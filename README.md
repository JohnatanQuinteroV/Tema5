# Tema5
# Laboratorio 5
# Respuestas

## Realizamos el siguiente análisis


#### Para tener al menos 1 cliente mas del 90\% del tiempo se necesita:
#### v <= 2.222
\nu
#### Se obtuvo utilizando las ecuaciones del enunciado
#### En el archivo .ipynb se explica l ecuación utilizada

### Modificaciones
### 1
 Parámetro de servicio (servicios/segundos)
nu = 2/60   #Cambiamos el valor, v=2
### 2
 Umbral de P o más personas en sistema (hay P - 1 en fila)
P = 1       #Cambiamos el valor, ponemos P=1
### 3
if fraccion >= 0.9:         #fraccion >= 0.9, ya que debe ser mayor al 90%
    print('\t Sí cumple con la especificación.')

