<h1 align="center">⚽ Análisis del rendimiento deportivo de la selección de fútbol de la Universidad de los Andes</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Estado-En%20desarrollo-yellow" />
  <img src="https://img.shields.io/badge/Proyecto-Ciencia%20de%20Datos-blue" />
  <img src="https://img.shields.io/badge/Año-2026-green" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2990BD&width=435&lines=Ciencia+de+datos+UNIANDES+|+2026" />
</p>

<p align="center">
  <img src="futbol.jpg" width="300">
</p>

<details>
  <summary> Integrantes </summary>

  <br>

  - Valeria Colmenares Moreno | 202610251
  - Juan Esteban Chaves Lesmes | 202614029
  - Alejandro Oconnor Morales | 202520801 
  - Angelica Parra Araque | 202614123

</details>

---

## Descripción
Este proyecto tiene como finalidad **analizar el rendimiento deportivo** de la selección de fútbol de la Universidad de los Andes.

A partir de datos de partidos y entrenamientos, se busca evaluar el rendimiento de los jugadores tomando en cuenta distintos factores como los resultados, la carga física y la participación en el juego. Además, el análisis permite identificar distintas situaciones como sobreentrenamiento, riesgo de lesiones o bajo rendimiento.

A traves de este proyecto, se garantizará demostrar como el uso de datos es útil para mejorar el rendimiento deportivo del equipo.

---

## Objetivos
- Evaluar el desempeño individual de los jugadores en partidos y entrenamientos.  
- Identificar patrones de alto y bajo rendimiento en el equipo.  
- Detectar posibles signos de sobrecarga física o riesgo de lesiones.
- Evaluar casos de bajo rendimiento asociados a poca participación. 
- Proponer recomendaciones para mejorar el desempeño y prevenir riesgos físicos. 

---

## Datos

El proyecto utiliza una serie de datos que representan el rendimiento de los jugadores en partidos y entrenamientos.

### Características de los datos
- Datos de jugadores de la selección de futbol 
- Registros de entrenamientos y partidos  
- Información sobre el desempeño deportivo  

### Variables 
- **id:** Código de estudiante del jugador.
- **Nombre:** Nombre completo del jugador.
- **Posición:** Posición en la que se desempeña el jugador.
- **Fecha:** Fecha de registro.
- **Tipo sesión:** Entrenamiento o partido. 
- **Minutos sesión:** Minutos de juego del jugador en la sesión, de 1 a 90.
- **Goles:** Número de goles del jugador en la sesión.
- **Asistencias:** Número de asistencias del jugador en la sesión.
- **Rendimiento (1-10):** Calificación dada por el entrenador al final de la sesión en una escala de 1-10 decimal.
- **Precisión:** Promedio del porcentaje de precisión de pases y disparos. 
- **Nivel de exigencia:** Dado por el director médico.  (Alto, medio, bajo). 
- **Riesgo de lesión:** Índice dado por el centro médico de la Universidad (Alto, medio, bajo). 

## Ejemplo de base de datos

| id | Nombre | Posición | Fecha | Tipo sesión | Minutos sesión | Goles | Asistencias | Rendimiento (1-10) | Precisión (%) | Nivel de exigencia | Riesgo de lesión | 
|----|--------|-----------|-------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| 202589897 | Juan Pérez | Delantero | 2026-01-10 | Partido | 76 | 2 | 2 | 9.5 | 74 | Alta | Alta | 
| 202378547 | Andrés Gómez | Portero | 2026-03-14 | Entrenamiento | 54 | 3 | 1 | 6.6 | 56 | Media | Bajo | 
| 202606750 | Mateo Torres | Mediocampo | 2026-03-04 | Partido | 90 | 0 | 3 | 8.8 | 78 | Media | Alta | 
| 202588791 | David López | Delantero | 2026-03-12 | Entrenamiento | 83 | 2 | 0 | 7.5 | 80 | Baja | Baja |
| 202568214 | Felipe Castro | Mediocampo | 2026-02-24 | Partido | 67 | 1 | 0 | 7.0 | 78 | Baja | Baja |
| 202467578 | Carlos Ruiz | Defensa | Dato 1 | 2026-03-12 | 88 | 0 | 0 | 6.4 | 23 | Alta | Alta |
