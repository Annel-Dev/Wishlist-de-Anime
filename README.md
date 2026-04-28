# Wishlist de Anime 🎬

Catálogo personal de animes pendientes de ver, organizado por géneros 
y presentado en tarjetas interactivas con imagen, descripción corta y 
sistema de calificación con estrellas.

## ✨ Características

- 📂 Organización por **4 géneros**: Romance, Isekai, Ciencia Ficción, Acción
- 🎴 Diseño tipo **card** con efectos hover suaves
- 📱 Layout **responsive** que se adapta al tamaño de pantalla
- ⭐ Sistema visual de **calificación con estrellas**
- 🎨 Paleta de colores **profesional** con variables CSS
- 🔠 Tipografía **Poppins** importada de Google Fonts

## 🛠️ Tecnologías

- **HTML5** — Estructura semántica con secciones por género
- **CSS3** — Variables, gradientes, flexbox, transiciones, pseudo-elementos
- **Google Fonts** — Tipografía Poppins

## 📚 Conceptos avanzados aplicados

### CSS

- **Variables CSS** (`:root`) para mantener paleta consistente en todo el sitio
- **Gradientes lineales y radiales** para fondos y acentos
- **Flexbox** para layout responsive de tarjetas (`flex-wrap`, `gap`, `justify-content`)
- **Pseudo-elementos** (`::after`) para detalles decorativos sin HTML extra
- **Transiciones suaves** con `transition` para hover effects
- **Transformaciones** con `transform: translateY()` y `transform: scale()` 
- **Object-fit** para control preciso de imágenes en contenedores
- **Letter-spacing** y `text-transform` para estética tipográfica
- **Box-shadow en capas** con cambio en hover para profundidad

### HTML

- Estructura jerárquica clara con `h1`, `h2` por sección
- Listas ordenadas anidadas en contenedores semánticos
- Atributos `alt` descriptivos en todas las imágenes

## 🎬 Animes incluidos (19 títulos)

**Romance**: Toradora · Horimiya · Kimi no Na wa · Clannad · Fruits Basket  
**Isekai**: Re:Zero · Sword Art Online · Overlord · That Time I Got 
Reincarnated as a Slime · No Game No Life  
**Ciencia Ficción**: Steins;Gate · Neon Genesis Evangelion · Psycho-Pass · 
Ghost in the Shell · Gurren Lagann  
**Acción**: Demon Slayer · Attack on Titan · My Hero Academia · 
One Punch Man · Naruto

## 📂 Estructura
proyecto/
├── index.html
├── stylo.css
└── Imagenes/
└── (portadas de todos los animes)

## 🚀 Cómo verlo

```bash
git clone https://github.com/Annel-Dev/nombre-del-repo.git
cd nombre-del-repo
```

Abre `index.html` en tu navegador.

## 📝 Notas

Este es uno de mis proyectos más completos hasta ahora en términos de 
CSS. Es donde por primera vez utilicé **variables CSS** para mantener 
consistencia y donde experimenté con **flexbox** para crear un layout 
de cards responsive. Los efectos hover y las transiciones le dan una 
sensación más cercana a un sitio profesional.

## 🎯 Mejoras futuras

- [ ] Migrar a CSS Grid para layout más controlado
- [ ] Añadir filtro por género con JavaScript
- [ ] Sistema de búsqueda
- [ ] Modo oscuro
