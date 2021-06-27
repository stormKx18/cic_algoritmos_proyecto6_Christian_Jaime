# Proyecto 6 - Disposición de grafos - parte II

[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)

**INSTITUTO POLITÉCNICO NACIONAL**

**Centro de Investigación en Computación**

**PRESENTA** Victor Christian Jaime Tamayo

**BOLETA** A210232

**ASIGNATURA** Diseño y Análisis de Algoritmos

**PROFESOR** Dr. Rolando Quintero Téllez

**SEMESTRE** A21

**FECHA** 21 de Junio de 2021

---

## Instrucciones

Dado un grafo, y utilizando pygame, generar una visualización del mismo. 
- Force-directed: calcula la disposición de un grafo mediante el algoritmo de equilibrio de fuerzas de Fruchterman y Reigold (1991). O(n^2)
- Mediante force-directed: utilizando la optimización de Barnes y Hut (1986). O(n log(n))

Entregables:
- Repositorio GIT
- Capturas de pantalla (links a videos) con la ejecución del proyecto. Dos por cada modelo de generación, uno con 100 nodos y otro con 500.

---

## Modelo Gm,n de malla
- m: número de columnas
- n: número de filas
- dirigido: el grafo es dirigido

##

### 100 nodos (Modelo Gm,n de malla)
**m = 10, n = 10, dirigido = False**

[![GRAFO_MALLA_100](/img/GRAFO_MALLA_100.PNG)](https://www.youtube.com/watch?v=UgdnvDPQOLs)

>[Ver en YouTube](https://www.youtube.com/watch?v=UgdnvDPQOLs)

##

### 506 nodos (Modelo Gm,n de malla)
**m = 23, n = 22, dirigido = False**

[![GRAFO_MALLA_500](/img/GRAFO_MALLA_500.PNG)](https://www.youtube.com/watch?v=U7OoQNJp6Jc)

>[Ver en YouTube](https://www.youtube.com/watch?v=U7OoQNJp6Jc)


##


---

## Modelo Gn,m de Erdös y Rényi
- n: número de nodos (> 0)
- m: número de aristas (>= n-1)
- dirigido: el grafo es dirigido?
- auto: permitir auto-ciclos?

##

### 100 nodos (Modelo Gn,m de Erdös y Rényi)
**n = 100, m = 100, dirigido = False, auto=False**

[![ERDOS_100](/img/ERDOS_100.PNG)](https://www.youtube.com/watch?v=y_b4q_hFS2g)

>[Ver en YouTube](https://www.youtube.com/watch?v=y_b4q_hFS2g)

##

### 500 nodos (Modelo Gn,m de Erdös y Rényi)
**n = 500, m = 500, dirigido = False, auto=False**

[![ERDOS_500](/img/ERDOS_500.PNG)](https://www.youtube.com/watch?v=u-RFw_K7kNs)

>[Ver en YouTube](https://www.youtube.com/watch?v=u-RFw_K7kNs)

##

---

## Modelo Gn,p de **Gilbert**
- n: número de nodos (> 0)
- p: probabilidad de crear una arista (0, 1)
- dirigido: el grafo es dirigido?
- auto: permitir auto-ciclos?

##

### 100 nodos (Modelo Gn,p de Gilbert)
**n = 100, p = 0.1, dirigido = False, auto=False**

[![GILBERT_100](/img/GILBERT_100.PNG)](https://www.youtube.com/watch?v=jWXKS2jQCEc)

>[Ver en YouTube](https://www.youtube.com/watch?v=jWXKS2jQCEc)


##


---

## Modelo Gn,r **geográfico simple**
- n: número de nodos (> 0)
- r: distancia máxima para crear un nodo (0, 1)
- dirigido: el grafo es dirigido?
- auto: permitir auto-ciclos?

##

### 100 nodos (Modelo Gn,r Geográfico simple)
**n = 100, r = 0.3, dirigido = False, auto=False**


[![GEOGRAFICO_100](/img/GEOGRAFICO_100.PNG)](https://www.youtube.com/watch?v=aL8Ht17KPKM)

>[Ver en YouTube](https://www.youtube.com/watch?v=aL8Ht17KPKM)

##

---

## Variante del modelo Gn,d **Barabási-Albert**
- n: número de nodos (> 0)
- d: grado máximo esperado por cada nodo (> 1)
- dirigido: el grafo es dirigido?
- auto: permitir auto-ciclos?

##

### 100 nodos (Variante del modelo Gn,d Barabási-Albert)
**n = 30, d = 4, dirigido = False, auto=False**

[![BARABASI_100](/img/BARABASI_100.PNG)](https://www.youtube.com/watch?v=RDpQ_V8KAfk)

>[Ver en YouTube](https://www.youtube.com/watch?v=RDpQ_V8KAfk)

##

### 500 nodos (Variante del modelo Gn,d Barabási-Albert)
**n = 500, d = 3, dirigido = False, auto=False**

[![BARABASI_500](/img/BARABASI_500.PNG)](https://www.youtube.com/watch?v=g2A535M5m1w)

>[Ver en YouTube](https://www.youtube.com/watch?v=p-gBZSHEjtU)

##

---

## Modelo Gn **Dorogovtsev-Mendes**
- n: número de nodos (≥ 3)
- dirigido: el grafo es dirigido?

##

### 100 nodos (Modelo Gn Dorogovtsev-Mendes)
**n = 30, dirigido = False**

[![DOROGVTSEV_100](/img/DOROGVTSEV_100.PNG)](https://www.youtube.com/watch?v=of-j_zOdstw)

>[Ver en YouTube](https://www.youtube.com/watch?v=of-j_zOdstw)

##

---
