
# MIRUTINA

Herramienta web estática para crear y gestionar rutinas de entrenamiento personalizadas de forma sencilla y visual.


## 🛠️ Características

* Hero impactante con fondo desenfocado (blur) y animaciones suaves.
* Navegación responsiva usando Bootstrap 5 y Font Awesome.
* Creación de rutinas: selecciona ejercicios, días y semanas.
* Listado de rutinas: visualiza, edita y elimina rutinas existentes.
* Modal de agregación de ejercicios con datos de series, repeticiones y día.
* Optimización SEO: meta tags, sitemap.xml y robots.txt.


## 🌐 Demo

Accede a la versión alojada en GitHub Pages:
https://sofiabolea.github.io/curso-desarrollo-web/


## Estructura de archivos
| Archivo / Carpeta       | Descripción                                   |
|-------------------------|-----------------------------------------------|
| `index.html`            | Página principal con sección Hero             |
| `estilos.scss`          | SCSS principal y partials                     |
| `estilos.css`           | CSS compilado                                |
| `multimedia/`           | Imágenes y recursos gráficos                 |
| `pages/`                | Páginas secundarias del sitio                 |
| ├─ `crearRutina.html`   | Formulario para crear rutinas                |
| ├─ `rutinas.html`       | Listado y edición de rutinas                 |
| ├─ `agregarEjercicio.html` | Agregar ejercicios a rutina                |
| ├─ `diaRutina.html`     | Vista de un día de rutina específico         |
| ├─ `diasRutina.html`    | Distribución semanal de rutinas              |
| ├─ `modificarRutina.html` | Editar rutinas existentes                  |
| ├─ `inicioSesion.html`  | Formulario de inicio de sesión               |
| └─ `registrarse.html`   | Registro de nuevos usuarios                  |
| `sitemap.xml`           | Mapa del sitio para SEO                      |
| `robots.txt`            | Control de rastreo para buscadores           |
| `README.md`             | Documentación del proyecto                   |

## ⚙️ Tecnologías

* HTML5
* SCSS (Sass)
* CSS3
* Bootstrap 5
* Font Awesome 6
* GitHub Pages para despliegue

## Detalles
La idea sería que todas las cosas que varian dependiendo del día, la rutina y demás se cargen con variables desde una base de datos. Por ahora las tablas estan cargadas todas iguales.
Además no permitiria el manejo de rutinas y demás sin antes iniciar sesión. Está pensada para que toda la validación se haga desde una base de datos