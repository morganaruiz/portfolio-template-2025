# portfolio-template-2025

Encuentra aquí el proyecto desplegado [https://morganaruiz.github.io/portfolio-template-2025/](https://morganaruiz.github.io/portfolio-template-2025/)

# Descripción y propósito del proyecto

En este proyecto se ha diseñado y creado una página web 1.0, en la cual muestro mi portfolio profesional como diseñadora gráfica e ilustradora. La estructura está implementada mediante HTML 5 y CSS 3, los principios de diseño responsive y estándares profesionales de desarrollo web. En esta página web enseño mis habilidades como diseñadora y muestro los diferentes tipos de trabajos que he realizado en los últimos años, cada uno perteneciendo a una categoría del diseño o del arte distinta.

Este proyecto tiene como finalidad es darme a conocer de forma internacional gracias a esta página web y, al mismo tiempo, mejorar y ampliar mis conocimientos sobre el diseño y desarrollo webapp.

# Stack tecnológico utilizado

- HTML5 para la estructura del sitio
- CSS3 para la maquetación y estilos
- JavaScript vanilla para la interacción
- Visual Studio Code para el desarrollo del proyecto
- GitHub Pages para el control de versiones y despliegue estático

# Instrucciones de configuración para desarrollo local

1. Asegúrate de tener instalado Git y un navegador moderno.

2. Clona el repositorio:
   git clone https://github.com/morganaruiz/portfolio-template-2025
   (o descarga el ZIP desde GitHub).

3. Abre el proyecto en Visual Studio Code.

4. (Opcional) Si tienes la extensión Live Server, inicia el servidor local haciendo clic en “Open with Live Server”.
   Si no la tienes, simplemente abre index.html en tu navegador.

5. El proyecto no requiere instalación de dependencias ni configuraciones adicionales, ya que está desarrollado con HTML5, CSS3 y JavaScript vanilla.

# Guía de personalización

Este proyecto utiliza una arquitectura modular de CSS para facilitar la escalabilidad y la personalización. A continuación se detalla qué contiene cada archivo y cómo modificarlo de manera segura según las necesidades del portfolio.

## 1. CSS

## 1.1 assets/css/base.css

Qué contiene:

Reset básico, variables iniciales y estilos globales aplicados al documento.

Qué puedes personalizar:

- Ajustes globales de tipografía.

- Reglas básicas del body, enlaces o elementos estándar.

- Cualquier estilo de arranque del proyecto.

## 1.2 assets/css/components.css

Qué contiene:

Estilos compartidos de componentes reutilizables: botones, tarjetas, bloques y elementos visuales comunes.

Qué puedes personalizar:

- Apariencia de botones.

- Tarjetas o módulos visuales.

- Cualquier componente repetido en varias secciones.

## 1.3 assets/css/index.css

Qué contiene:

Archivo “barrel”. Centraliza y agrupa todos los imports de los demás archivos CSS.

Qué puedes personalizar:

- Generalmente nada. Su función es organizativa, no de estilo.

- Solo toca este archivo si necesitas añadir o eliminar un módulo CSS.

## 1.4 assets/css/layout.css

Qué contiene:

Utilidades y reglas relacionadas con layout, grid, flexbox, espaciados estructurales, contenedores y distribución.

Qué puedes personalizar:

- Estructura de columnas.

- Alineaciones y contenedores.

- Espaciados entre secciones.

## 1.5 assets/css/navigation.css

Qué contiene:

- Estilos exclusivos de la barra de navegación:

  - Posicionamiento fijo.

  - Estilo del contenedor.

  - Logo.

  - Espaciado entre enlaces.

  - Hover states.

Qué puedes personalizar:

- El aspecto del menú.

- Colores de hover.

- Tipografía usada en la navegación.

- Transiciones y espaciados.

## 1.6 assets/css/theme.css

Qué contiene:

- Núcleo del sistema visual del proyecto. Incluye:

  - Variables de tipografía fluidas (clamp).

  - Escala de espaciado responsiva.

  - Paleta de colores completa.

  - Variables de animación.

  - Familias tipográficas.

  - Tokens de diseño reutilizables.

Qué puedes personalizar:

- Colores principales y secundarios.

- Tipografía global del proyecto.

- Tamaños de texto.

- Escala de espaciados.

- Duración y curvas de animación.

## 2. Imágenes y recursos

## 2.1 assets/images/

- Contiene las imágenes del portfolio:

  - Fondos de secciones.

  - Imágenes decorativas.

  - Imágenes de proyectos.

Puedes reemplazar imágenes manteniendo el mismo nombre o actualizar la ruta desde index.html.

## 2.2 assets/fonts/

Aquí puedes agregar o reemplazar tipografías personalizadas.

## 2.3 assets/favicon/

Favicons utilizados por el sitio. Se pueden sustituir sin afectar al funcionamiento.

## 3. JavaScript

## 3.1 assets/js/main.js

Qué contiene:

- Animaciones de scroll usando IntersectionObserver para elementos individuales y contenedores escalonados.

- Smooth scroll profesional para enlaces internos con ajuste por menú fijo y actualización de URL.

- Resalte de la sección activa en el menú usando IntersectionObserver.

- Inicialización de funciones al DOMContentLoaded y soporte para initTheme().

- Limpieza de observers para evitar fugas de memoria en SPAs.

Qué puedes personalizar:

- Animaciones y transiciones CSS.

- Offset y comportamiento del smooth scroll.

- Colores y estilos de la sección activa en el menú.

- Habilitar/deshabilitar módulos comentando las funciones en DOMContentLoaded.

- Llamar a cleanupScrollObservers() en SPAs si es necesario.

# 4. HTML

## 4.1 index.html

Qué contiene:

Toda la estructura del contenido del sitio: secciones, textos, imágenes y markup principal.

Qué puedes personalizar:

- Textos y títulos.

- Estructura de secciones.

- Rutas de imágenes.

- Ajustes de contenido.

## 4.2 404.html

Página de error personalizada para GitHub Pages.

- Textos y títulos.

- Estructura de secciones.

- Rutas de imágenes.

- Ajustes de contenido.

## Créditos y agradecimientos

Al profesor: Gracias por la guía, feedback y apoyo durante el desarrollo del proyecto :D

Recursos externos:

- Imágenes:
  Todas las ilustraciones del sitio web han sido dibujadas y diseñadas por mí.
  Los gifs de los pequeños gatos en el carrusel de la sección de About me pertenecen al sitio web https://pixelsafari.neocities.org/favicon/
  El gif que se ha empleado en la página de Error 404 pertenece al sitio web https://tenor.com/es/view/john-travolta-gif-12608206659263100219

- Íconos:
  El icono que he usado como favicon en el html pertenecen al sitio web https://es.pinterest.com/pin/464293042848376195/

El icono que he usado como favicon en el Error 404 pertenecen al sitio web https://es.pinterest.com/pin/312859505385787202/

- Fuentes:
  Las fuentes utilizadas son: ArialNarrow https://online-fonts.com/fonts/arial-narrow y Aston Script https://www.dafont.com/es/aston-script.font

Inspiración:
Use de plantilla uno de los ejemplos que puso el profesor en clase https://ruvebal.github.io/emofolio-template/

También me basé en la estética minimalista, el glasmorphismo y el neuformismo.

Herramientas: Visual Studio Code, Photoshop, Illustrator, Mediabang Paint Pro.
