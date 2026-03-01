# Carrusel-de-Cattleyas-creadas-con-Pollinations
Carrusel en el que las imágenes se pasan una a una con botones de anterior/siguiente, ideal si se quieren ver en orden.
# 🌺 Presentación Cattleya - Galería de Orquídeas

Una elegante aplicación web de presentación de diapositivas dedicada al género de orquídeas *Cattleya*, diseñada con un estilo visual sofisticado y cinematográfico.

## ✨ Características

### Diseño Visual
- **Estética cinematográfica**: Fondos oscuros (#0a0906) con acentos dorados (#d4a84b) y crema (#f2e8d5)
- **Tipografía elegante**: Combina Cinzel (serif decorativa) y EB Garamond (serif clásica)
- **Efectos visuales**: 
  - Transiciones suaves de opacidad (1s)
  - Efecto Ken Burns en imágenes (zoom gradual durante 6s)
  - Vignette oscuro en las diapositivas
  - Glassmorphism en controles (backdrop-filter: blur)

### Funcionalidad de Presentación
- **Navegación intuitiva**: Botones de anterior/siguiente con flechas
- **Indicador de progreso**: Barra de temporizador con gradiente de colores (orchid → gold → orange)
- **Contador de diapositivas**: Muestra posición actual (ej: "1 / 4")
- **Puntos de navegación**: Indicadores circulares interactivos en la parte inferior
- **Pausa/Reanudar**: Control de reproducción automática

### Contenido Educativo
Cada diapositiva incluye:
- Categoría taxonómica (ej: "C. aurantiaca")
- Nombre científico completo (*Cattleya aurantiaca*)
- Tipo de ilustración (ej: "Ilustración Botánica diseñada en Pollinations con nanobanana")

## 🛠️ Tecnologías

| Aspecto | Tecnología |
|---------|-----------|
| Estructura | HTML5 semántico |
| Estilos | CSS3 con variables CSS personalizadas |
| Tipografía | Google Fonts (Cinzel, EB Garamond) |
| Imágenes | Data URIs (WebP en base64) |
| Interactividad | JavaScript vanilla |

## 🎨 Paleta de Colores

```css
--bg: #0a0906        /* Fondo oscuro casi negro */
--gold: #d4a84b      /* Dorado principal */
--gold-dim: #8a6a28  /* Dorado atenuado */
--cream: #f2e8d5     /* Crema/claro */
--orchid: #b06090    /* Rosa orquídea */
--orange: #d4622a    /* Naranja terracota */
--text-dim: #7a6a55  /* Texto atenuado */

Esta aplicación es un ejemplo bien estructurado de una presentación web elegante, ideal para museos, jardines botánicos o exposiciones de arte naturalista. El código es limpio, modular y fácilmente extensible para agregar más especies de orquídeas.
