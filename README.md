# Taller 1 - Fundamentos Web
 
## Información del estudiante
 
**Nombre:** Valeria Gongora Montaño  
**Carrera:** Ingeniería en Sistemas  
**Semestre:** 4 semestre  
**Grupo:** 4303  
 
## Descripción del proyecto
 
Este repositorio contiene el desarrollo del Taller 1 de Fundamentos Web de UNICAMACHO.
 
El proyecto consiste en la creación de una página web utilizando únicamente HTML5 y GitHub, sin utilizar CSS, JavaScript, Bootstrap ni frameworks.
 
La página contiene información personal y académica, intereses, lenguajes de programación, enlaces de aprendizaje, imágenes, audio, video, horario académico y un formulario de contacto.
 
## Estructura del proyecto
 
```text
fundamentos-web-taller1/
├── index.html
├── README.md
└── multimedia/
    ├── imagen1.jpg
    ├── imagen2.jpg
Información académica

Estudio Ingeniería en Sistemas y actualmente curso cuarto semestre.

Mis intereses
Programación
1. Desarrollo de software
2. Bases de datos
 Lenguajes y tecnologías
1. JavaScript
2. Python
3. C++
| Asignatura          | Día       | Hora          | Modalidad  |
| Fundamentos Web     | Jueves    | 7:00 - 10:00  | Presencial |
| Cálculo Vectorial   | Miércoles | 7:00 - 10:00  | Presencial |
| Electrónica Digital | Martes    | 7:00 - 10:00  | Presencial |
| Laboratorio         | Lunes     | 10:00 - 13:00 | Presencial |
| Programación        | Viernes   | 10:00 - 13:00 | Presencial |

Verificación de código
Caso A

Problema identificado:
La etiqueta <img> utiliza el atributo href, pero este atributo no es el adecuado para indicar la ubicación de una imagen.

Corrección realizada:
Se cambió el atributo href por src.

Código corregido:

<img src="multimedia/perfil.jpg" alt="Fotografía del estudiante">

Fuente consultada:
MDN Web Docs - Elemento <img>.

Caso B

Problema identificado:
La etiqueta <a> utiliza el atributo src, pero para los enlaces se debe utilizar href.

Corrección realizada:
Se cambió src por href.

Código corregido:

<a href="https://developer.mozilla.org/">
    Consultar MDN
</a>

Fuente consultada:
MDN Web Docs - Elemento <a>.

Caso C

Problema identificado:
La etiqueta <source> utiliza el atributo href para indicar el archivo de video.

Corrección realizada:
Se cambió href por src.

Código corregido:

<video controls>
    <source src="multimedia/video.mp4" type="video/mp4">
</video>

Fuente consultada:
MDN Web Docs - Elemento <source>.

    ├── audio.mp3
    └── video.mp4
