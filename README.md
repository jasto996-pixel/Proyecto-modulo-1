# TukiPatas 🐾

Una plataforma de servicios y productos premium para mascotas que fusiona la atención veterinaria profesional con la tecnología moderna. TukiPatas es un sitio web responsivo que showcasea servicios especializados, productos de calidad y el equipo de expertos detrás de esta iniciativa.

---

## 📋 Descripción del Proyecto

TukiPatas nació de la necesidad compartida entre amantes de los animales: encontrar un lugar donde la calidad profesional se encuentre con el cuidado del hogar. Desde su fundación, la plataforma se ha transformado en una comunidad vibrante que conecta a dueños de mascotas con veterinarios, entrenadores y especialistas en cuidado animal.

Este sitio web presenta:
- **Catálogo de Productos y Servicios**: Muestra productos y servicios premium para mascotas
- **Sección de Categorías**: Organización clara de servicios veterinarios, productos y entrenamiento
- **Testimonios**: Reseñas y comentarios de usuarios satisfechos
- **Historia del Equipo**: Narrativa de TukiPatas y la filosofía de cuidado integral
- **Contacto**: Formulario para consultas y solicitudes de servicios
- **Carrito de Compras**: Sistema completo de compra de productos

---

## ✨ Características Principales

✅ **Diseño Responsivo** - Adaptado perfectamente a dispositivos móviles, tablets y desktop  
✅ **Navegación Intuitiva** - Menú sticky con búsqueda de productos  
✅ **Galería de Productos** - Imágenes con efectos hover interactivos  
✅ **Sistema de Carrito** - Gestión completa de compras  
✅ **Formulario de Contacto** - Con validación y diseño moderno  
✅ **Página 404 Personalizada** - Con redirección al inicio  
✅ **Redes Sociales** - Enlaces a Instagram, Facebook y más  
✅ **Sección Acerca de Nosotros** - Presenta el equipo de expertos  
✅ **Página de Login/Registro** - Autenticación de usuarios  
✅ **Comentarios de Productos** - Reseñas de usuarios

---

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica y accesible
- **CSS3** - Estilos personalizados con variables CSS
- **Bootstrap 5.3** - Framework responsivo
- **Bootstrap Icons** - Iconografía consistente
- **JavaScript** - Interactividad e movimientos interactivos
- **Google Fonts** - Tipografías modernas

---

## 📁 Estructura del Proyecto

```
tukipatas/
├── index.html                      # Página principal
├── pages/
│   ├── registro.html               # Página de registro
│   ├── login.html                  # Página de login
│   ├── detalle-del-producto.html   # Detalle de producto individual
│   ├── carrito.html                # Carrito de compras
│   ├── nosotros.html               # Información del equipo (Acerca de)
│   └── contactos.html              # Formulario de contacto
├── css/
│   ├── style.css                   # Estilos principales
│   ├── login-registro.css          # Estilos para login y registro
│   └── product-cart.css            # Estilos para productos y carrito
├── img/
│   ├── logotipo.png                # Logo del sitio
│   ├── imagotipo.png               # Imagotipo
│   ├── seccion1/                   # Imágenes de primera sección
│   ├── seccion2/                   # Imágenes de segunda sección
│   ├── seccion3/                   # Imágenes de tercera sección
│   ├── avatares/                   # Fotos del equipo
│   ├── imagnes-pagina-principal/   # Imágenes principales
│   └── (diversos productos y referencias)
└── README.md                       # Este archivo
```

---

## 🚀 Cómo Usar

### Instalación Local

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/tukipatas.git
cd tukipatas
```

2. **Abrir en navegador**
    - Opción 1: Hacer doble click en `index.html`
    - Opción 2: Usar Live Server (extensión de VS Code)
    - Opción 3: Abrir con un servidor local (`python -m http.server 8000`)

### Navegación del Sitio

| Página | Archivo | Descripción |
|--------|---------|------------|
| **Inicio** | `index.html` | Página principal con slider y categorías |
| **Registro** | `pages/registro.html` | Formulario de registro de usuarios |
| **Login** | `pages/login.html` | Formulario de autenticación |
| **Producto** | `pages/detalle-del-producto.html` | Detalle y descripción de producto |
| **Carrito** | `pages/carrito.html` | Gestión de compras y total |
| **Nosotros** | `pages/nosotros.html` | Información del equipo de TukiPatas |
| **Contacto** | `pages/contactos.html` | Formulario para consultas y mapa |

---

## 📱 Responsive Design

El sitio utiliza Bootstrap Grid System con breakpoints:

- **Mobile (xs)**: < 576px - 1 columna
- **Small (sm)**: ≥ 576px - 1-2 columnas
- **Medium (md)**: ≥ 768px - 2-3 columnas
- **Large (lg)**: ≥ 992px - 3-4 columnas
- **Extra Large (xl)**: ≥ 1200px - 3-4 columnas

Todos los elementos (imágenes, formularios, grillas de productos) se adaptan automáticamente.

---

## 🎯 Páginas Principales

### Página Principal (index.html)
- Navegación con busqueda de productos
- Secciones de productos ordenadas en categorías
- Slider/carrusel de promociones
- Links de navegación a todas las secciones
- Footer con información y redes sociales

### Registro (pages/registro.html)
- Formulario de registro de nuevos usuarios
- Campos: nombre, apellido, email, teléfono, domicilio, código postal, contraseña
- Validación de formulario
- Estilos personalizados en login-registro.css

### Login (pages/login.html)
- Formulario de autenticación
- Opciones de login con Google/Facebook
- Link de recuperación de contraseña
- Validación de credenciales
- Estilos en login-registro.css

### Detalle de Producto (pages/detalle-del-producto.html)
- Imagen principal del producto
- Título, precio y descripción detallada
- Botón "Agregar al carrito"
- Sección de comentarios/reseñas
- Productos relacionados

### Carrito de Compras (pages/carrito.html)
- Tabla/lista con productos seleccionados
- Cantidad y precio de cada producto
- Botones para eliminar productos
- Total a pagar
- Botón para proceder con la compra
- Estilos en product-cart.css

### Acerca de Nosotros (pages/nosotros.html)
- Historia y misión de TukiPatas
- Galería de fotos del equipo (avatares circulares)
- Descripción de valores y filosofía
- Información del equipo

### Contacto (pages/contactos.html)
- Mapa con ubicación de la empresa
- Formulario de contacto con validación
- Campos para nombre, email, asunto y mensaje
- Información de contacto directo

---

## 📋 Estilos y Personalización

Los estilos principales están en `css/style.css`. Puedes personalizar:

- **Colores**: Variables CSS en la parte superior del archivo
- **Fuentes**: Importadas de Google Fonts
- **Componentes**: Cards, botones, modales, etc.
- **Iconos de Bootstrap**: Utiliza Bootstrap Icons para iconografía consistente
- **Movimientos con JavaScript**: Animaciones y transiciones interactivas (scroll, hover, fade-in, etc.)

---

## 🚢 Deployment

### Opción 1: GitHub Pages
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

En GitHub:
1. Settings → Pages
2. Source: main branch
3. Save

### Opción 2: Netlify
1. Conectar repositorio
2. Build command: (dejar en blanco para sitios estáticos)
3. Publish directory: `/`
4. Deploy

---

## 📞 Equipo de Desarrollo 

| Integrante | Rol |
|-----------|-----|
| **Amalia Fernández** | Scrum Master / Desarrolladora |
| **Ricardo Vosahlo** | Desarrollador |
| **Rosario Maria De Los Ángeles Pierrestegui** | Desarrolladora |
| **Tomás Saucedo** | Desarrollador |
| **Nahir Pérez Muze** | Desarrolladora |

---

## 📞 Contacto

**Desarrolladora/Scrum Master**: Amalia Fernández  
**Email**: m.amalia.fernandez@gmail.com  
**LinkedIn**: https://www.linkedin.com/in/amalia-fernandez-1317162b/
----
**Desarrolladora**: Rosario María de los Ángeles Pierrestegui
**LinkedIn**: https://rollingcodeschool.slack.com/archives/C0B4LMD3YRZ/p1779892268722719
---

- El proyecto es estático (HTML/CSS/JavaScript vanilla)
- Para funcionalidad de pagos, registro y base de datos necesitarás un backend
- Las imágenes son placeholders - reemplazalas con las reales de TukiPatas
- El carrito actualmente funciona con JavaScript (datos en memoria)
- Para persistencia de datos, considera implementar una API backend

---



**Hecho con ❤️ para TukiPatas - Cuidado con Corazón**