# Unidad 1

## 🔎 Fase: Set + Seek

## Actividad1🚀
### ¿Qué es el diseño generativo?:
- Es un conjunto de reglas y instrucciones que genera unas amplias "maneras" de diseño, es utilizada para generar un amplio repertorio de diseños, en el diseño generativo el artista se vuelve un arquitecto ya que él es quien realiza los algoritmos, variaciones o restricciones que se traducen en un conjunto de "soluciones"
### ¿Qué es el arte generativo?:
- Hace caso a parametros muy parecidos de el diseño generativo, en este el artista tambien crea una serie de algoritmos y reglas que van a generar el arte, la diferencia mas notable es que en el arte generativo hay mas "libertad creativa", es algo que transmite mas emociones por asi decirlo, en cambio con el diseño hay un objetivo que seria resolver unos problemas con esos algoritmos creados
### ¿Cuál es la diferencia entre el diseño/arte generativo vs el diseño/arte tradicional?:
- De a primeras notamos una clara diferencia, el artista generativo trabaja con una maquina que traduce una serie de reglas y algoritmos en un conjunto de soluciones (pueden ser miles) que nos daria un amplio panorama de soluciones o arte, en cambio el diseñador/artista tradicional trabaja para crear un numero mas pequeño de soluciones/arte basado en su experiencia
### ¿Qué posibilidades crees que esto puede ofrecer a tu perfil profesional?📘
- En mi perfil profesional no estoy tan seguro de que me pueda ofrecer, claramente es una herramienta que al dia de hoy es muy util y no se puede descartar la posibilidad de que en un futuro lo pueda usar, lo que creeria que me puede ofrecer es una serie de soluciones amplia para tener mas contenido que sirva para el problema que se me presente en algun momento
----
## Actividad 2🎱
### Antes de lo que hemos discutido, ¿Qué pensabas que hacía un Ingeniero en diseño de entretenimiento digital con énfasis en experiencias interactivas?🧰
- Un ingeniero en diseño de entretenimiento digital con enfasis en experiencias pensaba que hacia por ejemplo scape rooms, o juegos con los que se pueden interactuar como por ejemplo los juegos que hacia Noel hace años, y creo que el pensamiento que tengo acerca de eso es muy acercado a lo que hacemos los ingenieros de entretenimiento en enfasis de experiencias, obviamente hacen muchas mas cosas que eso que menciono pero es una idea que no esta tan alejada
### ¿Qué potencial le ves al diseño e implementación de experiencias inmersivas colectivas?
- Siento que es una nueva forma de entretenimiento, mucho mas interesante para el public, ya que siendo algo inmersivo, el usuario puede vivir la "experiencia" de manera diferente mucho mejor en temas de inmersion, ademas el tema de que sea inmersiva y colectiva fomenta la colaboracion para solucionar retos o lo que sea que proponga la experiencia, puede ser util en educacion o simplemente en entretenimiento 
### Nosotros estamos definiendo en TIEMPO REAL una nueva forma de expresión, una nueva forma de interactuar de manera colectiva. Estamos diseñando nuevas maneras de contar historias e interactuar con ellas. ¿Cómo te ves profesionalmente en este escenario?
- Tal vez me veria diseñando las ideas de las experiencias interactivas y colaborando con centros comerciales que tengo la idea de que son uno de los establecimientos que le dan la oportunidad a instalar experiencias dentro de sus edificios, tambien me gustaria explorar en las narrativas que van con las experiencias ya que es un tema que me interesa mucho
----
## Actividad 3💻
### Enlace al sketch original:
- https://editor.p5js.org/generative-design/sketches/P_2_2_5_01
- Este sketch es algo sencillo de entender, se generan circulos aleatoriamente por la pantalla, cuando das click izquierdo sostenido y vamos moviendo el cursor por la pantalla se para la generacion automatica de circulos y empezamos a generar los circulos nosotros mismos
### Enlace a sketch modificado:
- https://editor.p5js.org/JuanGonzalezAr/sketches/V521T4lxp
```js
minRadius = map(mouseX, 0, width, 3, 20);
maxRadius = map(mouseX, 0, width, 20, 80);
```
- Cuando se mueve el mouse mas a la izquierda horizontalmente se hacen circulos mas pequeños, cuando se mueve mas a la derecha se hacen circulos mas grandes, esto se agrego en el draw donde el bloquesito de codigo de antes es para calcular el radio de los circulos y que no se sobrepongan
