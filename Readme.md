Infografía Científica: Desarrollo Sostenible
Descripción
Este proyecto consiste en una infografía interactiva desarrollada en HTML y CSS, basada en el análisis de un paper científico sobre el desarrollo de competencias para la sostenibilidad en estudiantes universitarios.
Contenido
La infografía presenta un "Top 5" de los hallazgos más importantes del estudio, incluyendo:
•	Influencia del entorno universitario
•	Diferencia entre aprendizaje académico y no académico
•	Importancia de los programas de estudio
•	Aprendizaje basado en problemas y proyectos
•	Modelo GreenComp
Tecnologías utilizadas
•	HTML5
•	CSS3
•	IA generativa (Z.ai)
Proceso de desarrollo
Primero se realizó la lectura y síntesis del paper científico. Luego, se elaboró un "super prompt" para generar el código de la infografía utilizando inteligencia artificial. Finalmente, el código fue convertido en un archivo HTML y desplegado mediante GitHub Pages.
Autor
Gabriel Adrian Navarro Puertas
PROMPT USADO:


 
Super Prompt: Infografía Interactiva De Lista (Modelo RISEN)

[Rol] Actúa como un desarrollador front-end experto, diseñador UI/UX y especialista en diseño de la información gráfica orientada a entornos educativos y digitales.

[Instrucción] Crea la estructura completa (HTML y CSS) para una infografía interactiva de tipo "De lista". El objetivo es presentar un conjunto secuencial de elementos (como un "top 5") de forma dinámica, transformando las viñetas tradicionales en iconos interactivos y aplicando un resaltado animado al texto cuando el usuario pase el cursor sobre cada ítem.

[Pasos]

Estructura Base (HTML): Diseña una lista semántica (<ul> o <ol>) con 5 elementos (<li>). Cada elemento debe tener dos columnas: a la izquierda un ícono, y a la derecha el texto (título + descripción).

Integración del Efecto Principal (CSS): Aplica el efecto de ícono con semicírculo usando border-radius: 50% y pseudoelementos (::before y ::after). Al hacer hover, el semicírculo debe rotar para completar el círculo.

Integración del Efecto Secundario (CSS): Aplica una línea ondulada animada debajo del título usando background-image en base64. Esta línea debe moverse horizontalmente con animación (@keyframes) al hacer hover.

Estilización: Usa tipografía sans-serif, buen espaciado, colores modernos y diseño limpio. Debe ser responsivo (mobile first).

[Contenido y Personalización]

Textos:

1. Título: Influencia del entorno universitario  
Descripción: El entorno universitario influye directamente en el desarrollo de competencias relacionadas con el desarrollo sostenible en los estudiantes.

2. Título: Diferencia entre aprendizaje académico y no académico  
Descripción: Las competencias de valores y complejidad se desarrollan en programas de estudio, mientras que las de acción se fortalecen fuera del entorno académico.

3. Título: Importancia de los programas de estudio  
Descripción: Los contenidos y estructura de los programas académicos son clave para formar competencias sostenibles.

4. Título: Aprendizaje basado en problemas y proyectos  
Descripción: Este tipo de aprendizaje impulsa el pensamiento creativo y la capacidad de actuar frente a problemas reales.

5. Título: Modelo GreenComp  
Descripción: El estudio se basa en 12 competencias del modelo GreenComp que organizan habilidades clave para el desarrollo sostenible.

Diseño Visual:

Colores:
#1E3A8A
#10B981
#F59E0B

Íconos:
1. 🎓
2. 🧠
3. 📚
4. 💡
5. 🌱

Pie de Página (Footer):
Incluir un <footer> al final que diga:

Fuente: The Importance of the University Environment in Shaping Competences Relating to Sustainable Development Among Geography Students in Poland and Czechia - DOI: https://doi.org/10.1007/978-3-031-81268-2_8

Diseñado por: Gabriel Adrian Navarro Puertas

[Fin]

Entrega el resultado en un solo archivo HTML que incluya el CSS dentro de <style>. No expliques nada, solo devuelve el código.

[Restricciones]

Usa solo HTML y CSS (sin JavaScript ni frameworks).
El CSS debe usar transition: all 0.4s ease-in-out.
El diseño debe ser responsivo y fácil de usar en móvil.
Incluye comentarios en el CSS explicando cómo modificar la animación y el SVG en base64
