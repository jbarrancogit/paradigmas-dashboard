# Paradigmas de Programacion - Dashboard Maestro de Estudio

Dashboard web interactivo para preparar el examen final de **Paradigmas de Programacion** (UTN - Facultad Regional Mendoza, Ing. en Sistemas de Informacion).

## Demo en vivo

**[Abrir Dashboard](https://jbarrancogit.github.io/paradigmas-dashboard/paradigmas_dashboard.html)**

## Que incluye

### Teoria completa (37 temas)
- **Java OO** (16 temas): objetos, herencia, polimorfismo, interfaces, generics, excepciones, threads, colecciones, persistencia y mas
- **Prolog** (11 temas): hechos, reglas, unificacion, backtracking, listas, corte, clausulas de Horn, resolucion
- **Haskell** (10 temas): funciones, pattern matching, tipos, listas, recursion, HOFs, currificacion, evaluacion perezosa, calculo lambda, data types

Cada tema tiene 5 secciones: concepto clave, aplicacion en el mundo real, ejemplo resuelto, trampa de examen, y pregunta tipo con resolucion guiada en 3 niveles.

### Examenes predichos (5 examenes, 140 preguntas)
Basados en el analisis de 20+ examenes reales (2019-2026), con preguntas extraidas directamente de finales anteriores. Cada pregunta tiene dropdown de 3 niveles: pista, razonamiento paso a paso, respuesta completa.

### Ejercicios practicos (40 ejercicios)
Todos los ejercicios de las 6 guias de TP de la catedra, cada uno con solucion completa paso a paso:
- TP1: Clases y Objetos
- TP2: Relaciones
- TP3: Aplicaciones
- TP4: Prolog (18 predicados)
- TP5: Haskell (13 funciones)
- TP6: UML a Codigo Java

### Simulacro de examen
Examen con timer, calificacion automatica y revision detallada. Configurable: 10/20/30 preguntas, 15/30/50 minutos. Incluye generador de examenes aleatorios infinitos.

### Flashcards
100+ tarjetas de estudio generadas de la teoria y examenes. Click para voltear, navegacion con flechas.

### Buscador global (Ctrl+K)
Busca en TODA la teoria, ejercicios y examenes al mismo tiempo.

### Inteligencia de catedra
- Banco de 20 examenes recopilados (2019-2026)
- Graficos de frecuencia de temas
- Patrones detectados del formato de examen
- Tips de supervivencia para el examen virtual

### Videos de la catedra
24 videos de clases organizados por paradigma (Java OO, Prolog, Haskell).

### Visualizaciones 3D
- Escena hero con esfera y anillos orbitales (Three.js)
- 3 arboles interactivos: resolucion Prolog con corte, backtracking, jerarquia Java
- 7 diagramas SVG en ejercicios

## Tecnologias

Un solo archivo HTML autocontenido (~5600 lineas). Sin instalacion, doble click para abrir.

- **Three.js** - Visualizaciones 3D
- **Chart.js** - Graficos estadisticos
- **Vanilla JS** - Sin frameworks
- **LocalStorage** - Progreso persistente

Requiere conexion a internet para las CDNs (Three.js, Chart.js, Google Fonts). La teoria y ejercicios funcionan offline.

## Basado en

- Programa de catedra UTN FRM (2019)
- 20+ examenes finales recopilados (2019-2026)
- 6 guias de trabajos practicos oficiales
- Bibliografia: Schildt "Java 7", Ruiz/Jimenez "Razonando con Haskell", Julian/Alpuente "Prog Logica", Bird "Intro Prog Funcional con Haskell"
- Libro "El Lenguaje de Programacion PROLOG" (Toledo, Pacheco, Escrig)

## Uso local

```bash
# Clonar
git clone https://github.com/jbarrancogit/paradigmas-dashboard.git

# Abrir (doble click o)
open paradigmas_dashboard.html
```
