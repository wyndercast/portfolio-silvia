# Reglas del agente para este proyecto

## Contexto del sitio

Este proyecto es una pagina web estatica para servicios legales relacionados con perros, familias multiespecie y negocios del sector PET. La marca gira alrededor de Silvia Rodriguez como abogada que acompana a tutores de perros ante conflictos de convivencia, propiedad horizontal, negligencias veterinarias y casos complejos que requieren estrategia legal y apoyo tecnico.

El enfoque principal debe ser humano, claro y profesional: defensa del vinculo con el perro, tranquilidad para el tutor, rigurosidad legal y educacion canina como complemento.

## Stack y alcance tecnico

- Trabajar con HTML puro en los archivos existentes de la raiz: `index.html`, `service.html`, `contact.html`, `portfolio.html`, `portfolio-detail.html` y `resume.html`.
- Mantener la estructura actual del template: Bootstrap, jQuery, plugins locales, `assets/css/style.css`, `assets/css/responsive.css` y assets existentes.
- No agregar frameworks, bundlers, CMS, backend, servicios externos, formularios dinamicos, dependencias de npm ni configuraciones complejas.
- No convertir el proyecto a React, Vue, Astro, Next, Vite u otra arquitectura.
- Evitar cambios grandes de CSS salvo ajustes puntuales necesarios para que una seccion existente funcione o se vea coherente.
- Preferir clases y patrones ya presentes en el template antes de crear nuevas abstracciones.

## Reglas de contenido

- Escribir el contenido en espanol, con tono cercano, juridico y tranquilizador.
- Usar un lenguaje directo para tutores de perros en Colombia: conflicto con vecinos, administracion, multas, convivencia, miedo a perder al perro, negligencias y busqueda de reparacion.
- Evitar textos genericos del template como "Lorem Ipsum", "Happy Client", "Creative Designer", "Portfolio", "Hire Me", "Project Complete" o referencias a tecnologia si no hacen parte del servicio.
- No prometer resultados legales garantizados. Usar mensajes de estrategia, acompaniamiento, defensa, gestion, prevencion y claridad.
- Mantener la idea central: "Tu perro no es el problema; la tenencia irresponsable, si".
- Cuidar que los llamados a la accion sean concretos: agendar asesoria, recuperar tranquilidad, conocer servicios, contactar.

## Secciones esperadas para el Home

Cuando se trabaje en `index.html`, priorizar estas secciones:

1. Header con logo, navegacion simple y enlaces a las paginas existentes.
2. Hero con Silvia Rodriguez, propuesta de valor y CTA principal.
3. Seccion de confianza: por que puede ayudar, basada en experiencia personal, derecho, dialogo y educacion canina.
4. Servicios principales:
   - Defensa en propiedad horizontal.
   - Responsabilidad medica y de servicios.
   - Alianza PET para casos complejos.
   - Consultoria corporativa sector PET.
   - Formacion y cursos para tutores y profesionales.
5. CTA intermedio sobre recuperar la paz con la familia multiespecie.
6. Seccion de situaciones frecuentes: presion de vecinos, cartas de administracion, amenazas de multas, incidentes, negligencias y conflictos escalados.
7. Testimonios o prueba social solo si hay contenido realista disponible; si no, reemplazar textos falsos por bloques informativos utiles.
8. Footer con datos reales o placeholders discretos, sin informacion falsa de otro template.

## Reglas visuales

- Mantener una estetica profesional, legal y cercana al mundo PET.
- Usar imagenes locales en `assets/images` cuando ya existan y sean pertinentes.
- No agregar decoraciones complejas, animaciones nuevas ni efectos que requieran nueva logica.
- No saturar la pagina con tarjetas si una seccion simple de texto y columnas resuelve mejor.
- Verificar que los textos no queden en ingles ni desbordados en botones, titulos o columnas.

## Reglas de edicion

- Antes de editar, revisar el HTML afectado y respetar cambios existentes del usuario.
- No tocar archivos binarios o imagenes salvo solicitud explicita.
- No eliminar assets, scripts o estilos del template si no es necesario para la tarea.
- Mantener cambios pequenos y localizados.
- Para cambios manuales usar `apply_patch`.
- Al terminar, revisar el resultado con una busqueda de textos residuales del template cuando aplique.

## Prioridad actual

La siguiente fase sera trabajar el Home de la pagina. Hasta que se solicite explicitamente, no implementar cambios visuales o de contenido en `index.html`.
