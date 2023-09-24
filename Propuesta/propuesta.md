<h3 align="center">Universidad de Buenos Aires</h3>
<h3 align="center">Facultad de Ingeniería</h3>
<p align="center">
  <a href="https://example.com/">
    <img src="img\logoFiuba.png" alt="Logo">
  </a>
  <h3 align="center">
    Propuesta de Trabajo Profesional
  </h3>
  <h3 align="center">
    Análisis de grafos Out of Core
  </h3>
</p>

- Leonardo Emmanuel Giampieri Mutti - 102358
- Joaquin Guido Hojman de la Rosa - 102264
- Francisco Manuel Vazquez Fernandez - 104128

<p align="center">
  <h6 align="center">
   Octubre 2023
  </h6>
</p>

## Índice

- [Índice](#índice)
- [Introducción](#introducción)
- [Estado de Situacíon](#estado-de-situacíon)
- [Objetivos](#objetivos)
- [Planificación de Trabajo](#planificación-de-trabajo)
- [Bibliografía](#bibliografía)

## Introducción

El siguiente documento presenta la propuesta de Trabajo Profesional de Ingeniería en
Informática de los estudiantes Leonardo Emmanuel Giampieri Mutti (padrón 102358), Joaquin Guido Hojman de la Rosa (padrón 102264) y Francisco Manuel Vazquez Fernandez (padrón 104128).

El objetivo del proyecto es aplicar los conocimientos adquiridos en la carrera. El tema elegido es ’Análisis de grafos Out of Core’.

En la era de la información digital, la generación y acumulación de datos se ha convertido en una actividad omnipresente en prácticamente todos los ámbitos de la sociedad. Este fenómeno ha dado lugar a una explosión de datos interconectados que se pueden representar y analizar eficazmente mediante la teoría de grafos. Los grafos, como modelos abstractos de relaciones entre entidades, han demostrado ser una herramienta poderosa para entender y extraer información valiosa de diversas fuentes de datos, desde redes sociales y sistemas de transporte hasta biología molecular y análisis financiero. Sin embargo, a medida que la cantidad de datos crece exponencialmente, surge un desafío fundamental: cómo analizar grafos enormes de manera eficiente.

## Estado de Situacíon

En el contexto del análisis de grafos, NetworkX ha emergido como una de las bibliotecas más utilizadas y versátiles para Python. Su popularidad radica en su facilidad de uso y su amplia gama de algoritmos y herramientas que permiten a los científicos de datos, investigadores y profesionales de diversos campos analizar y comprender las relaciones y estructuras en los datos interconectados. Sin embargo, a medida que las aplicaciones del análisis de grafos se expanden para abordar conjuntos de datos más grandes y complejos, NetworkX se encuentra con ciertas limitaciones relacionadas con la carga y el manejo de grafos de gran tamaño.

La importancia y relevancia del análisis de grafos "out of core" se refleja en una serie de aplicaciones y casos de estudio actuales. Por ejemplo, en el campo de las redes sociales, el análisis de la propagación de información, la detección de comunidades y la identificación de actores clave en redes con millones de nodos y conexiones es crucial para comprender la difusión de información y la toma de decisiones colectivas. En bioinformática, el análisis de grafos se utiliza para comprender las interacciones de proteínas y genes, lo que puede llevar al descubrimiento de tratamientos para enfermedades. Además, en el ámbito financiero, la detección de anomalías y la gestión de riesgos requieren el análisis de grandes redes de transacciones financieras.

La capacidad de cargar y analizar grafos grandes es esencial en estas y muchas otras aplicaciones, ya que permite revelar patrones ocultos, tomar decisiones informadas y obtener información valiosa de los datos masivos. Sin embargo, este desafío va más allá de simplemente lidiar con la limitación de la memoria; implica diseñar algoritmos eficientes y estrategias de almacenamiento inteligentes para garantizar que el análisis de grafos sea factible y efectivo en un entorno de recursos limitados.

La importancia de proyectos de código abierto como NetworkX no puede subestimarse. Estos proyectos permiten el acceso libre y gratuito a herramientas poderosas, lo que democratiza la ciencia de datos y la investigación en grafos. Facilitan la colaboración y el intercambio de conocimientos a nivel global, alentando a la comunidad a contribuir con mejoras y correcciones de errores. 

## Objetivos

1. Facilitar el Análisis de Grafos a Gran Escala: El objetivo final es proporcionar a los usuarios de NetworkX una solución eficaz para el análisis de grafos de gran tamaño, permitiéndoles aprovechar al máximo las capacidades out-of-core sin comprometer la simplicidad y la flexibilidad que caracterizan a la biblioteca.

2. Desarrollar una Nueva Clase de Grafo Out-of-Core: Se buscará diseñar e implementar una nueva clase de grafo en NetworkX que sea capaz de gestionar grafos de gran tamaño, permitiendo su almacenamiento y acceso por partes en el disco. Esto permitirá que los grafos que excedan la memoria principal de una máquina puedan ser cargados y analizados de manera eficiente, evitando la limitación de la memoria.

3. Implementar Estructuras Intermedias: Se desarrollarán las estructuras de datos intermedias necesarias para el funcionamiento de los algoritmos de análisis de grafos en el contexto out-of-core. Estas estructuras deberán optimizarse para minimizar el tiempo de acceso a los datos en disco y garantizar un rendimiento eficiente en la manipulación de los grafos.

4. Mantener las Convenciones de NetworkX: Se procurará que la nueva implementación y las modificaciones introducidas mantengan la coherencia con las convenciones y la filosofía de diseño de NetworkX. Esto incluirá la adherencia a las prácticas y convenciones de nomenclatura establecidas en NetworkX, de modo que los usuarios existentes puedan aprovechar las nuevas capacidades sin tener que realizar cambios significativos en su código.

5. Evaluar el Rendimiento y la Usabilidad: Se llevarán a cabo pruebas exhaustivas para evaluar el rendimiento de la nueva implementación y se recopilarán comentarios de los usuarios para garantizar que las modificaciones introducidas sean efectivas y fáciles de usar en escenarios del mundo real.

## Planificación de Trabajo

Please read through our [contributing guidelines](https://reponame/blob/master/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, all HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Main author](https://github.com/usernamemainauthor).

Editor preferences are available in the [editor config](https://reponame/blob/master/.editorconfig) for easy use in common text editors. Read more and download plugins at <https://editorconfig.org/>.

## Bibliografía

**Creator 1**

- <https://github.com/usernamecreator1>
