# SoyControl - Landing Page

Landing page corporativa para SoyControl desarrollada con Astro y TailwindCSS.

## 🚀 Características

- **Framework**: Astro 5.0+ para máximo rendimiento
- **Estilos**: TailwindCSS para diseño responsivo y moderno
- **Optimización**: Imágenes optimizadas y SEO integrado
- **Componentes**: Sistema de componentes reutilizables
- **Analytics**: Integración con Firebase Analytics
- **Deployment**: Configurado para Firebase Hosting

## 📁 Estructura del Proyecto

```
/
├── public/
│   ├── robots.txt
│   └── _headers
├── src/
│   ├── assets/
│   │   ├── images/        # Imágenes del sitio
│   │   └── styles/        # Estilos CSS
│   ├── components/
│   │   ├── ui/            # Componentes de interfaz
│   │   ├── widgets/       # Widgets reutilizables
│   │   └── common/        # Componentes comunes
│   ├── layouts/           # Layouts de página
│   ├── pages/             # Páginas del sitio
│   └── utils/             # Utilidades y helpers
├── astro.config.ts
├── firebase.json
└── package.json
```

## 🛠️ Instalación y Desarrollo

### Requisitos previos
- Node.js 18.17.1+ o 20.3.0+ o 21.0.0+
- npm o yarn

### Instalación
```bash
# Clonar el repositorio
git clone <repository-url>
cd sc-landing-page

# Instalar dependencias
npm install
```

### Comandos disponibles

| Comando                | Descripción                              |
| ---------------------- | ---------------------------------------- |
| `npm run dev`          | Inicia el servidor de desarrollo        |
| `npm run build`        | Construye el proyecto para producción   |
| `npm run preview`      | Previsualiza la build de producción     |
| `npm run check`        | Verifica código (Astro, ESLint, Prettier) |
| `npm run fix`          | Arregla automáticamente issues de código |

## 📄 Páginas Principales

- **Inicio** (`/`) - Página principal con hero y features
- **Acerca de** (`/about`) - Información sobre SoyControl
- **Servicios** (`/services`) - Servicios ofrecidos
- **Precios** (`/pricing`) - Planes y precios
- **Contacto** (`/contact`) - Formulario de contacto
- **Blog** (`/blog`) - Artículos y noticias

## 🎨 Componentes Principales

### Widgets
- `Hero` - Sección principal de landing
- `Features` - Características del producto/servicio
- `Testimonials` - Testimonios de clientes
- `CallToAction` - Llamadas a la acción
- `Contact` - Formulario de contacto
- `Pricing` - Tablas de precios

### UI
- `Button` - Botones reutilizables
- `Form` - Componentes de formulario
- `Headline` - Títulos y subtítulos
- `ItemGrid` - Grillas de elementos

## 🚀 Deployment

El proyecto está configurado para Firebase Hosting:

```bash
# Build y deploy
npm run build
firebase deploy
```

## 🔧 Configuración

La configuración principal se encuentra en:
- `src/config.yaml` - Configuración del sitio y SEO
- `astro.config.ts` - Configuración de Astro
- `firebase.json` - Configuración de Firebase

## 📱 SEO y Performance

- Metadatos optimizados para SEO
- Open Graph y Twitter Cards
- Imágenes optimizadas automáticamente
- Sitemap generado automáticamente
- RSS feed incluido

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

---

Desarrollado con ❤️ para SoyControl
