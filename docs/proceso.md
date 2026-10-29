# Proceso de implementación — SOKACH

## Propósito de este documento

Registrar el trabajo realizado, las decisiones de implementación, los resultados comprobados y los pendientes del proyecto.

Este registro se inició después de las primeras tareas. La etapa inicial se reconstruye a partir de capturas conservadas y comprobaciones realizadas durante el desarrollo.

No representa una aprobación del cliente ni sustituye el acuerdo de alcance.

## Punto de partida

El proyecto comenzó con un documento de referencia entregado por el cliente y la preparación de un entorno local en WordPress.

Se decidió utilizar una plantilla prediseñada como base de implementación, adaptándola posteriormente a SOKACH.

La plantilla seleccionada contiene una identidad de clínica dental. Sus textos, imágenes, logo y elementos de reservas no representan a SOKACH.

## Hito 1 — Revisión inicial de requisitos

### Necesidad

Comprender la estructura solicitada antes de comenzar la construcción.

### Trabajo realizado

- Tomar el documento del cliente como referencia.
- Identificar las áreas principales del sitio.
- Separar necesidades de contenido, funcionalidades y decisiones pendientes.
- Preparar una estructura inicial para trabajar en WordPress.

### Resultado

Se estableció una base de trabajo para organizar el sitio.

### Pendientes

- Consolidar por escrito el alcance definitivo.
- Confirmar funcionalidades, exclusiones y criterios de aprobación.
- Verificar qué materiales fueron recibidos y cuáles están aprobados para publicar.
- Confirmar la solución definitiva para inscripción de socios.

## Hito 2 — Entorno local operativo

### Necesidad

Disponer de un espacio para construir y probar el sitio antes de publicarlo.

### Trabajo realizado

- Creación del sitio SOKACH en LocalWP.
- Acceso al escritorio de WordPress.
- Comprobación de la visualización del sitio local.

### Resultado comprobado

El escritorio y la portada local abren correctamente.

### Pendientes

- Registrar las versiones técnicas verificadas.
- Crear y comprobar un respaldo antes de cambios importantes.

## Hito 3 — Importación de una plantilla base

### Necesidad

Contar con una estructura visual inicial editable.

### Decisión de implementación

Se seleccionó la plantilla “Dentist Clinic” desde Starter Templates.

La elección se basó en su apariencia relacionada con el ámbito de la salud y en una combinación inicial de azules y turquesas que podía servir como referencia visual.

Esta decisión de implementación no se considera una aprobación del diseño por parte del cliente.

### Trabajo realizado

- Selección de la plantilla.
- Selección de una paleta inicial aproximada.
- Importación del sitio de demostración.
- Comprobación de que la importación finalizó.

### Resultado comprobado

La portada importada se visualiza en el entorno local.

### Limitaciones

La plantilla conserva contenido dental que debe reemplazarse.

La paleta seleccionada es provisional y no equivale a la aplicación de los colores institucionales exactos.

## Hito 4 — Limpieza inicial

### Necesidad

Retirar elementos de demostración y reservas que no se utilizarían en esta etapa.

### Trabajo realizado

- Desactivación y eliminación del plugin LatePoint.
- Envío a la papelera de las dos páginas “Customer Cabinet”.
- Envío a la papelera de “Página de ejemplo”.
- Conservación de la portada.
- Conservación de Política de privacidad como borrador.

### Resultado comprobado

Después de eliminar LatePoint, la portada continuó abriendo sin problemas.

### Limitaciones

Esta comprobación no constituye una prueba completa de todas las secciones ni de los formularios.

### Pendientes

- Revisar si quedaron botones, enlaces o elementos asociados a reservas.
- Evaluar la necesidad de los plugins restantes.
- Revisar los archivos multimedia importados.

## Hito 5 — Creación de la estructura de páginas

### Necesidad

Reemplazar la organización de demostración por una estructura institucional.

### Trabajo realizado

Se crearon las siguientes páginas internas:

- Quiénes somos.
- Directiva actual.
- Kinesiología acuática.
- Hazte socio.
- Noticias y actividades.
- Contacto.

La portada “Home” se renombró como “Inicio”.

### Resultado comprobado

La lista de páginas muestra las siete páginas principales, incluida Inicio.

Inicio conserva su asignación como página principal y su contenido creado con Elementor.

Política de privacidad permanece como borrador.

### Limitaciones

Las páginas internas fueron creadas como estructura inicial. Sus contenidos y diseños todavía no están terminados.

## Hito 6 — Configuración del menú principal

### Necesidad

Mostrar las páginas de SOKACH en lugar de la navegación de demostración.

### Trabajo realizado

- Retirada de los enlaces personalizados Home, About, Procedures, Reviews y Contact.
- Incorporación de las páginas reales del proyecto.
- Organización del orden de navegación.
- Guardado del menú.
- Asignación a la ubicación “Menú principal”.

### Orden configurado

1. Inicio.
2. Quiénes somos.
3. Directiva actual.
4. Kinesiología acuática.
5. Hazte socio.
6. Noticias y actividades.
7. Contacto.

### Resultado comprobado

El menú aparece en el encabezado de la portada local.

### Observaciones

- El menú ocupa dos filas en la captura revisada.
- El encabezado conserva el logo dental.
- El botón “Get Appointment” sigue visible y presenta un corte de texto.
- La imagen principal y el formulario mantienen contenido de demostración.

### Pendientes

- Probar individualmente todos los enlaces.
- Ajustar el espacio disponible en la cabecera.
- Revisar la navegación en móvil.
- Adaptar el botón principal según el alcance confirmado.

## Estado al cerrar esta primera etapa

### Comprobado

- Entorno local operativo.
- Plantilla importada.
- Limpieza inicial realizada.
- Estructura de páginas creada.
- Menú guardado y visible en la portada.
- Portada accesible después de retirar LatePoint.

### No completado

- Identidad visual institucional.
- Adaptación de la portada.
- Contenidos de páginas internas.
- Configuración definitiva de formularios.
- Sistema de noticias.
- Pruebas completas.
- Revisión del cliente.
- Publicación y entrega.

## Evidencias disponibles

Se conservan capturas de:

- Selección de la plantilla.
- Opciones e importación.
- Plugins instalados.
- Limpieza de páginas.
- Creación de las páginas institucionales.
- Renombrado de Home a Inicio.
- Configuración y guardado del menú.
- Visualización de la portada con la nueva navegación.

Estas capturas deben revisarse antes de publicarse para ocultar correos, pestañas personales y otros datos innecesarios.

## Aprendizajes

- Una plantilla requiere revisar sus dependencias, no solo su apariencia.
- Las páginas y los elementos de menú son componentes distintos.
- Guardar un menú y asignarlo a una ubicación son pasos diferentes.
- La configuración debe comprobarse también en la vista del sitio.
- Una estructura navegable no equivale a un sitio terminado.
- Las decisiones deben documentarse sin confundir propuestas con aprobaciones.

## Próximo hito — Adaptación de la cabecera

### Objetivo

Comenzar a sustituir la identidad dental por la identidad de SOKACH.

### Antes de intervenir

- Guardar una captura del estado actual.
- Crear un respaldo.
- Revisar las opciones de Aspecto → Personalizar.
- Verificar la disponibilidad y autorización del logo.
- Confirmar el destino del botón principal.

### Evidencia que se registrará

- Captura del antes.
- Cambios realizados y motivo.
- Captura del resultado.
- Comprobaciones en escritorio y móvil.
- Pendientes encontrados.
