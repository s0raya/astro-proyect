# 📚 Documentación FullStack Developer

Un sitio web de documentación construido con **Astro**, que presenta contenido educativo sobre desarrollo FullStack, incluyendo fundamentos de programación, desarrollo backend y frontend.

## ✨ Características

- 🚀 **Construido con Astro** - Framework moderno y rápido para sitios estáticos
- 📝 **Sistema de contenido** - Gestión de contenido mediante Astro Content Collections
- 🎨 **Diseño responsive** - Interfaz adaptativa para todos los dispositivos
- 🔍 **Navegación intuitiva** - Breadcrumbs y sistema de búsqueda
- 💻 **Editor de código integrado** - Componente personalizado para mostrar ejemplos de código
- 🎯 **Componentes accesibles** - Implementación de componentes accesibles
- 📱 **Transiciones suaves** - View Transitions para una mejor experiencia de usuario


## 📁 Estructura del Proyecto

```
astro-portfolio/
├── public/
│   └── images/          # Imágenes y assets estáticos
├── src/
│   ├── components/      # Componentes reutilizables
│   │   ├── Card.astro
│   │   ├── CodeEditor.astro
│   │   ├── Modal.astro
│   │   └── Navbar.astro
│   ├── content/         # Contenido en Markdown
│   │   ├── bases_de_datos/
│   │   ├── css/
│   │   ├── html/
│   │   ├── javascript/
│   │   └── nodejs/
│   ├── layouts/         # Layouts de página
│   │   ├── BlogPost.astro
│   │   └── Layout.astro
│   ├── pages/           # Páginas y rutas
│   │   ├── fundamentals/
│   │   ├── backend/
│   │   ├── frontend/
│   │   └── index.astro
│   └── styles/          # Estilos globales
│       ├── global.css
│       └── custom-breadcrumbs.scss
├── astro.config.mjs     # Configuración de Astro
├── package.json
└── tsconfig.json
```

## 🚀 Instalación

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/s0raya/astro-proyect.git
   cd astro-portfolio
   ```

2. **Instala las dependencias**
   ```bash
   npm install
   ```

## 📜 Scripts Disponibles

- `npm run dev` o `npm start` - Inicia el servidor de desarrollo en `http://localhost:4321`
- `npm run build` - Construye el sitio para producción en la carpeta `dist/`
- `npm run preview` - Previsualiza la versión de producción localmente

## 📖 Contenido

El sitio está organizado en tres secciones principales:

### 🎓 Fundamentals
- **HTML** - Elementos semánticos, formularios, tablas, etc.
- **CSS** - Flexbox, Grid, animaciones, responsive design, etc.
- **JavaScript** - Variables, funciones, objetos, promesas, async/await, etc.

### ⚙️ Backend
- **Node.js** - Express, APIs REST, middlewares, diseño modular, etc.
- **Bases de Datos** - MongoDB, SQL, Mongoose, etc.

### 🎨 Frontend
- **React** - Framework de desarrollo frontend

## 🌐 Despliegue

El proyecto está configurado para desplegarse en **GitHub Pages**.

El sitio estará disponible en: `https://s0raya.github.io/astro-proyect/`

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👤 Autor

**Soraya Alcobet** - [GitHub](https://github.com/s0raya)

---

⭐ Si este proyecto te resulta útil, ¡no olvides darle una estrella!

