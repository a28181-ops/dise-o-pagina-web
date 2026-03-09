# Jornada Tecnológica Zaragoza 2026

## Descripción del proyecto
Este sitio web es una landing page diseñada para la promoción de la **Jornada Tecnológica Zaragoza 2026**. El objetivo principal es informar a los usuarios sobre el evento y facilitar su inscripción a través de una interfaz moderna y adaptativa.

## Estructura de Columnas (Bootstrap 5)
Para el diseño visual, se ha utilizado el sistema de rejilla de Bootstrap:
* **Sección de Información**: Se organiza en una fila con tres columnas de tamaño `col-md-4` para mostrar los datos clave (Qué, Cuándo, Dónde) de forma paralela en escritorio.
* **Sección de Actividades**: Utiliza dos columnas de tamaño `col-lg-6`, dividiendo el espacio equitativamente entre el texto descriptivo y la imagen del evento.

## Componentes de Bootstrap usados
* **Navbar**: Barra de navegación superior con estilo oscuro y enlaces alineados a la derecha.
* **Hero Section**: Contenedor con imagen de fondo personalizada y llamadas a la acción.
* **Botones**: Uso de clases `btn-primary`, `btn-success` y `btn-lg` para destacar las acciones de inscripción.
* **Utilidades de espaciado**: Clases como `my-5`, `mb-4` y `p-4` para gestionar márgenes y rellenos de forma coherente.

## Historial de Commits
* **Commit 1**: Maquetación con columnas bootstrap y header con menú de navegación
* **Commit 2**: Creación de la sección "Hero" con imagen de fondo técnica y título principal.
* **Commit 3**: Implementación de la sección informativa usando el sistema de tres columnas responsivas.
* **Commit 4**: Desarrollo de la sección de actividades con listas de puntos e imagen.
* **Commit 5**: Finalización del proyecto con el pie de página (footer) y ajustes en la navegación.

## Dificultad y Solución
**Dificultad**: La principal complicación fue separar los elementos del menú en la barra de navegación, ya que Bootstrap los agrupaba demasiado estrechamente de forma predeterminada.

**Solución**: Se optó por una solución sencilla y efectiva añadiendo entidades de espacio en blanco (`&nbsp;`) directamente en el código HTML para separar los enlaces del menú sin necesidad de reglas CSS adicionales.
