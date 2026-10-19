<div align="center">

<img src="logo.png" alt="Logotipo de La Bohemia Lanzarote" width="125">

# La Bohemia · Lanzarote

### Landing page de restaurante con diseño editorial, animaciones y experiencia responsive

**Desarrollo frontend · Web corporativa · HTML, CSS y JavaScript**

![HTML5](https://img.shields.io/badge/HTML5-1A1B26?style=for-the-badge&logo=html5&logoColor=E46B79)
![CSS3](https://img.shields.io/badge/CSS3-1A1B26?style=for-the-badge&logo=css3&logoColor=E46B79)
![JavaScript](https://img.shields.io/badge/JavaScript-1A1B26?style=for-the-badge&logo=javascript&logoColor=E46B79)
![Responsive](https://img.shields.io/badge/Responsive-1A1B26?style=for-the-badge&logo=css3&logoColor=E46B79)

[![Estado](https://img.shields.io/badge/ESTADO-Web_frontend-712B39?style=flat-square)](#estado-del-proyecto)
[![Tipo](https://img.shields.io/badge/TIPO-Landing_page-22252C?style=flat-square)](#sobre-el-proyecto)
[![Código](https://img.shields.io/badge/REPOSITORIO-Código_fuente-22252C?style=flat-square)](https://github.com/fmoorenoo/la_bohemia)

</div>

---

## Sobre el proyecto

**La Bohemia · Lanzarote** es una propuesta de página web para un restaurante de **Costa Teguise, Lanzarote**. Presenta el establecimiento mediante una experiencia visual de estilo editorial, con tipografía cuidada, fotografía gastronómica, animaciones y secciones de navegación orientadas a dar a conocer su oferta.

La implementación utiliza **HTML5, CSS3 y JavaScript sin frameworks**. El código de la página, los estilos y la lógica de interacción se encuentran en `index.html`, acompañados por imágenes y vídeos locales.

> Este repositorio contiene el desarrollo de una web de presentación. Su publicación en GitHub no acredita, por sí sola, que sea la web oficial actual del establecimiento ni que sus contenidos comerciales estén actualizados.

## Funcionalidades

- **Presentación visual:** portada a pantalla completa, fotografías y recursos audiovisuales.
- **Navegación por secciones:** acceso a experiencia, especialidades, galería, carta, reseñas y reservas.
- **Diseño responsive:** adaptación mediante reglas CSS específicas para diferentes tamaños de pantalla.
- **Menú móvil:** navegación desplegable para pantallas pequeñas.
- **Animaciones y efectos:** transiciones, elementos decorativos y comportamiento interactivo en JavaScript.
- **Galería gastronómica:** imágenes del local, platos y espacios.
- **Información de contacto:** enlaces externos a WhatsApp, ubicación en mapas y redes sociales.

La sección de reservas ofrece vías de contacto externas. **No se ha identificado un backend propio ni un sistema integrado que almacene y gestione reservas.**

## Tecnologías

| Área | Tecnologías |
| --- | --- |
| **Estructura** | HTML5 |
| **Estilos y diseño** | CSS3 · variables CSS · media queries |
| **Interactividad** | JavaScript (vanilla) · DOM |
| **Tipografía** | Google Fonts: Playfair Display, Cormorant Garamond y DM Sans |
| **Iconografía** | Font Awesome |
| **Contenido multimedia** | Imágenes JPG/PNG · vídeo MP4 |
| **Enlaces externos** | WhatsApp · Google Maps · redes sociales |

## Arquitectura

```text
la_bohemia/
├── index.html                   # Página, estilos y JavaScript
├── logo.png                     # Identidad visual
├── hamburguesa.jpg              # Fotografía gastronómica
├── carne.jpg                    # Fotografía gastronómica
├── postre.jpg                   # Fotografía gastronómica
├── vinos.jpg                    # Fotografía gastronómica
├── terraza.jpg                  # Fotografía del establecimiento
├── decoracion.jpg               # Recursos visuales
├── decoración_interior.jpg      # Recursos visuales
├── cartel_exterior.jpg          # Recursos visuales
├── vid.mp4                      # Vídeo de la página
└── ...                          # Otros recursos multimedia
```

**Nota técnica:** se trata de una implementación monolítica en un único documento HTML. Para facilitar el mantenimiento futuro, podría separarse el CSS y el JavaScript en archivos específicos.

## Diseño y recursos

<div align="center">
  <img src="terraza.jpg" alt="Fotografía de la terraza utilizada en la web" width="75%">
  <p><sub>Imagen incluida entre los recursos originales del proyecto.</sub></p>
</div>

| Gastronomía | Ambiente |
| :---: | :---: |
| <img src="carne.jpg" alt="Fotografía gastronómica del proyecto" width="100%"> | <img src="decoracion.jpg" alt="Fotografía de decoración del establecimiento" width="100%"> |

Las imágenes anteriores son **recursos del sitio**, no capturas de la interfaz en ejecución.

## Instalación y ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/fmoorenoo/la_bohemia.git
   cd la_bohemia
   ```

2. Abre `index.html` en un navegador moderno.

Para probar la página desde un servidor HTTP local:

```bash
python -m http.server 8000
```

Después visita `http://localhost:8000/`.

La web no requiere instalar dependencias con npm para visualizar la implementación existente. Algunas fuentes e iconos necesitan conexión a Internet porque se cargan desde servicios externos.

## Estado del proyecto

**Desarrollo frontend de una página de presentación de restaurante.** El repositorio incluye una implementación estática con interacciones en el navegador.

Aspectos a revisar antes de utilizarla como sitio comercial en producción:

- **Contenido comercial:** confirmar cartas, precios, horarios, datos de contacto y enlaces.
- **Reservas:** los enlaces de contacto no equivalen a un sistema de gestión de reservas integrado.
- **Rendimiento:** existen varios vídeos y fotografías; conviene optimizar formatos, tamaños y carga.
- **Mantenimiento:** separar HTML, CSS y JavaScript facilitaría futuras modificaciones.
- **Accesibilidad y calidad:** no se han realizado pruebas sistemáticas de accesibilidad, rendimiento o compatibilidad durante esta revisión.
- **Recursos multimedia:** comprobar los derechos y permisos de uso de las imágenes y vídeos antes de redistribuirlos.

## Autor

**Fernando Montelongo Moreno** · Full Stack Developer · DAM + DAW

[![GitHub](https://img.shields.io/badge/GitHub-fmoorenoo-22252C?style=flat-square&logo=github)](https://github.com/fmoorenoo)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil_profesional-712B39?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/fernando-montelongo/)

---

<div align="center">
  <sub>La Bohemia · Lanzarote · Proyecto de desarrollo frontend</sub>
</div>
