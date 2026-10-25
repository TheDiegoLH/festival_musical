Este proyecto es un simulador de festival musical desarrollado en Python. El objetivo es aplicar los conceptos de herencia, polimorfismo y redefinición de métodos en un contexto creativo: distintos tipos de artistas se presentan en un festival y cada uno actúa de manera diferente, aunque todos comparten la misma interfaz de presentación y despedida.
El sistema permite registrar cantantes, DJs y bandas, validar sus atributos y simular sus actuaciones de manera polimórfica, sin necesidad de condicionales para distinguir tipos.
El proyecto está organizado en dos archivos principales:

clases/artistas.py: contiene la clase base Artista y las clases derivadas Cantante, DJ y Banda.

main.py: programa principal que interactúa con el usuario, registra artistas y ejecuta el festival.

La estructura de carpetas es la siguiente:
festival_musical/
│
├─ main.py
└─ clases/
   └─ artistas.py
Descarga el proyecto desde GitHub en formato ZIP.

Haz clic en el botón verde Code en el repositorio.

Selecciona Download ZIP.

Extrae el contenido en tu computadora.

Abre una terminal en la carpeta del proyecto.

Ejecuta el programa con: python main.py
Funcionamiento
Al iniciar el programa, se te preguntará cuántos artistas participarán en el festival.
Por cada artista deberás ingresar:

Tipo de artista (Cantante, DJ o Banda).

Nombre.

Género musical (solo se aceptan géneros permitidos).

Popularidad (un número entre 1 y 100).

Atributo específico según el tipo:

Cantante → canción más popular.

DJ → estilo musical.

Banda → número de integrantes.

El sistema validará los datos y, si son correctos, registrará al artista.
Finalmente, se ejecutará el festival mostrando las presentaciones, actuaciones y despedidas de cada artista.
