Hospital Central — Portal Clínico y Sitio Informativo
Proyecto web multipágina desarrollado en HTML puro (con estilos en línea y navegación mediante rutas relativas) para una tarea académica de la carrera Tecnología Superior Universitaria en Desarrollo de Software en PUCE Tec (Pontificia Universidad Católica del Ecuador).

Autoría
Desarrollado por: Ariel Palma

Institución: PUCE Tec

Carrera: Tecnología Superior Universitaria en Desarrollo de Software

Estructura del proyecto
index.html

imgs/

pages/portal_clinico.html

pages/ayuda.html

pages/historial_clinico.html

Páginas incluidas
index.html: Página principal con encabezado, navegación, especialidades médicas, horarios de atención y recomendaciones previas a la consulta.

pages/portal_clinico.html: Acceso al portal clínico y enlaces a las demás secciones del sitio.

pages/historial_clinico.html: Formulario de registro de historia clínica con agrupación mediante <fieldset> y <legend>, campos de identificación, signos vitales, motivo de consulta, enfermedad actual, carga de exámenes y tipo de sangre.

pages/ayuda.html: Guía rápida para pacientes y preguntas frecuentes desplegables con <details> y <summary>.

Cambios realizados para ejecutar la página en la web (GitHub Pages)
Reemplazo de rutas absolutas por rutas relativas: Se sustituyeron las rutas iniciadas con / (como /imgs/..., /pages/... y /index.html) por rutas relativas (./ desde la raíz y ../ desde la carpeta pages/), ya que en GitHub Pages la barra / apunta a la raíz del dominio y no a la subcarpeta del repositorio.

Estructura de carpetas compatible: Se mantuvo index.html en la raíz del repositorio y las carpetas imgs/ y pages/ al mismo nivel para que los enlaces e imágenes resuelvan correctamente al publicarse mediante GitHub Pages (Settings > Pages > Deploy from a branch).

Ajustes de marcado HTML: Se corrigieron cierres de etiquetas, filas de tabla (<tr> dentro de <thead>) y referencias de id/for en los formularios para mantener una estructura válida en el navegador.
