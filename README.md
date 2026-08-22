Manual de Usuario y Documentación (README)
Aplicación Interactiva: Romanos 9 y 10 — Soberanía, Elección y Fe
Esta aplicación web interactiva de una sola página (SPA) ha sido diseñada como una herramienta educativa y de estudio activo para explorar en profundidad los conceptos teológicos de Romanos 9 y 10. El contenido y la estructura de la aplicación están estrictamente basados y fundamentados en los materiales de tus fuentes: Concurso y Soberanía Divina y el Camino de la Fe en Romanos.

📌 Resumen de la Aplicación
La aplicación se compone de una interfaz moderna y adaptativa (responsive) estructurada en dos secciones principales de aprendizaje activo:

Tarjetas Didácticas (Flashcards) en 3D:

Permite repasar preguntas clave sobre el sentir misionero de Pablo, el propósito de la elección y la justificación.
Cuenta con un efecto visual de giro en tres dimensiones al hacer clic sobre la tarjeta para revelar la respuesta bíblica exacta.
Cuestionario Evaluativo (Quiz):

Consta de 5 preguntas de opción múltiple con opciones y respuestas literales basadas en los pasajes bíblicos clave.
Implementa un sistema de control que bloquea el avance hasta que la pregunta activa sea respondida.
Ofrece retroalimentación de color instantánea (verde para aciertos, rojo para fallos) acompañada de un recuadro con explicaciones y justificaciones teológicas detalladas para cada respuesta.
🗂️ Fundamento del Contenido (Grounding)
Las tarjetas y preguntas del cuestionario se basan estrictamente en la síntesis y los pasajes textuales provistos por tus fuentes:

El Sentir de Pablo: Basado en Romanos 9:2, que describe el profundo dolor y la "gran tristeza y continuo dolor" del apóstol por sus hermanos alejados.
El Propósito de la Elección: Basado en Romanos 9:16, reafirmando que no depende del esfuerzo humano ("del que quiere, ni del que corre"), sino del favor soberano y la "misericordia" de Dios.
El Error de Israel: Basado en Romanos 9:32, detallando el tropiezo por buscar la justicia mediante las "obras de la ley" y no por la "fe".
El Celo sin Ciencia: Basado en Romanos 10:2, para describir la pasión espiritual desprovista del conocimiento de la Verdad ("celo de Dios, pero no conforme a ciencia").
Creer y Confesar: Basado en Romanos 10:10, que sintetiza el camino de salvación ("con el corazón se cree para justicia, pero con la boca se confiesa para salvación").
La Cadena Misionera: Basado en Romanos 10:14-15, que expone el proceso lógico del evangelismo: enviar, predicar, oír, creer e invocar al Señor.
La Metáfora del Alfarero: Basada en la soberanía divina ilustrada en Romanos 9, donde el Creador tiene el derecho absoluto sobre el barro para manifestar su misericordia y gracia, uniendo a judíos y gentiles en la adopción espiritual a través de Cristo.
🚀 Instrucciones de Instalación y Ejecución
Para ejecutar esta aplicación localmente en tu computadora o dispositivo móvil, no requieres de servidores ni instalaciones complejas de software. Sigue estos sencillos pasos:

Copiar el Código: Copia el bloque de código completo (HTML, CSS y JavaScript) proporcionado en la conversación anterior.
Crear el Archivo: Abre tu editor de texto favorito (como Bloc de notas, VS Code, Sublime Text o TextEdit) y crea un nuevo archivo en blanco.
Guardar el Archivo: Pega el código copiado dentro del archivo y guárdalo exactamente con el nombre: index.html (asegúrate de que la extensión sea .html y no .txt).
Abrir la Aplicación: Haz doble clic sobre el archivo index.html que acabas de guardar. Se abrirá automáticamente de forma local en tu navegador web de preferencia (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge, etc.) listo para ser usado de manera offline.
🎨 Guía de Personalización Técnica
El código fue estructurado de manera modular para facilitar modificaciones sin necesidad de alterar la lógica del programa:

A. Cambiar o Añadir Preguntas del Quiz
Las preguntas se encuentran almacenadas dentro de la constante de JavaScript quizData al final del documento HTML. Para añadir o cambiar una pregunta, busca este bloque:

const quizData = [
    {
        question: "Tu pregunta aquí...",
        options: [
            "Opción A",
            "Opción B",
            "Opción C",
            "Opción D"
        ],
        correct: 2, // Índice de la respuesta correcta (0 para A, 1 para B, 2 para C, etc.)
        explanation: "Explicación teórica de la respuesta."
    },
    ...
];
B. Modificar la Paleta de Colores
En la parte superior de la etiqueta <style>, encontrarás las variables de diseño CSS (:root). Puedes cambiar estos códigos hexadecimales para adaptar la interfaz a tu gusto:

:root {
    --primary: #1e1b4b;        /* Color principal oscuro (barra, botones, textos de títulos) */
    --primary-light: #312e81;  /* Color del botón al pasar el cursor y detalles adicionales */
    --accent: #b45309;         /* Color de acento cálido */
    --success: #047857;        /* Color de retroalimentación para respuestas correctas */
    --danger: #be123c;         /* Color de retroalimentación para respuestas incorrectas */
    --bg: #f8fafc;             /* Color de fondo general de la pantalla */
    --card-bg: #ffffff;        /* Fondo blanco de tarjetas y contenedores */
}
Desarrollado y fundamentado en el análisis teológico de Romanos 9 y 10.
