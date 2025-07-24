# Unidad 1

## 🛠 Fase: Apply
## Actividad 5:
### Select🔨
- http://www.generative-gestaltung.de/2/sketches/?01_P/P_2_0_01

### Describe📝
- Este interesante sketch se trata de que a medida que vas moviendo el cursor se van generando unas "lineas" mas gruesas hasta que se generen un circulo completamente negro que seria teniendo el cursor en lo mas bajo del lienzo, a medida que se mueve al medio se hace mas pequeño pero unicamente al medio, a la derecha o izquierda el circulo se vuelve mas grande, esto seria solo la parte baja del lienzo del sketch, en la parte de arriba funciona un poco parecido solo que las lineas son de menos `radio` hacia la izquierda son menos lineas (pueden llegar a ser 2) y hacia la derecha hasta 8, una particularidad que me di cuenta es que funciona como una rueda, hice el ejercicio de por maso menos el borde del lienzo darle la vuelta al cursor a ver que pasaba y lo que vi es que de derecha a izquierda de arriba a abajo se van generando mas lineas y por consiguiente se llena el circulo, lo mismo pasa si lo hago al reves, es decir de izquierda a derecha y de arriba a abajo, a primera vista podria deducir que se usan funciones como cos y sen para calcular posiciones del circulo

### Analize🤔
- Aunque no se ven a simple vista, este sketch tiene conexiones internas importantes. Usa funciones matemáticas como map(), cos() y sin() para traducir el movimiento del mouse en posiciones exactas en el lienzo. También hay una relación invisible entre el número de líneas y la posición vertical del mouse, así como entre el tamaño del dibujo y la posición horizontal
### Convert 🇨🇴
- https://editor.p5js.org/JuanGonzalezAr/sketches/kzaeZpKHX
- Empecé intentando `recrear` algo que ya había visto o usado antes. Lo primero fue centrar el círculo, para lo cual utilicé translate(), una función que ya conocía. Luego intenté crear el círculo desde cero, pero al final necesité revisar el sketch original porque no lograba obtener el efecto deseado. Descubrí que la clave era el ciclo for, que permite dibujar múltiples líneas formando un círculo. También tuve dificultades con el cálculo del ángulo y el radio, ya que los estaba usando al revés, lo que impedía que las líneas se generaran correctamente. Finalmente entendí que las funciones cos() y sin() eran esenciales: se encargan de calcular la posición horizontal y vertical de cada punto alrededor del centro del lienzo. Esa parte es el corazón del sketch.
### Explore 📱
- Primero empece cambiando el color del sketch, luego queria implementar una `duplicacion` de circulos, es decir, queria probar si se podia poner 2 circulos en el sketch y ver como se comportaba con una funcion translate, estuve intentando con ciclos for y de las formas que probe no me funciono entonces decidi cambiarle solo el color, tambien cambie el numero de lineas que se generan que se cambio en el circle ratio.

<img width="1628" height="903" alt="evidencias" src="https://github.com/user-attachments/assets/ffd87a52-bc0f-4339-82c1-816f80217150" />



### Tinker 🤔
- Modifique el storkeWeight para tratar de romper el curso normal del sketch en vez de un mouseY implemente un mouseX que no dejaba crear el circulo o agrandarlo de tamaño y que creara las lineas normales que se crean, tambien intercambie los parametros de radio y angulo que dañan completamente el sketch y eliminan tambien la funcion de el sketch original, aqui tambien intente crear 2 circulos con un ciclo for para un translate y ver como se comportaba y literalmente se me cerro el programa, no me funciono mas y me tocaba cerrarlo
<img width="1314" height="651" alt="Evidencia1" src="https://github.com/user-attachments/assets/4c4c2759-d9eb-4794-9636-0be4077eb8b9" />
<img width="1897" height="1012" alt="image" src="https://github.com/user-attachments/assets/40049c57-ceba-492f-b88b-c0c75435ee90" />








