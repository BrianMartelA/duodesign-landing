# Duodesign Landing Page

Aplicación Angular para el landing page de DuoDesign, diseñada por Jose y Brian Martel.

## Estructura del Proyecto

```
src/
├── app/
│   ├── components/
│   │   ├── header/          # Navegación principal
│   │   ├── hero/           # Sección hero con presentación
│   │   ├── services/       # Servicios ofrecidos
│   │   ├── about/          # Información sobre los hermanos
│   │   ├── contact/        # Información de contacto
│   │   └── footer/         # Pie de página
│   ├── app.component.*     # Componente raíz
│   ├── app.module.ts       # Módulo principal
│   └── app-routing.module.ts # Configuración de rutas
├── styles.css              # Estilos globales con Tailwind CSS
└── index.html             # Punto de entrada de la aplicación
```

## Tecnologías Utilizadas

- **Angular 17** - Framework principal
- **Tailwind CSS** - Framework de estilos CSS utility-first
- **TypeScript** - Lenguaje de programación
- **Google Fonts** - Fuentes personalizadas (Inter y Poppins)
- **Material Symbols** - Iconografía

## Scripts Disponibles

### Desarrollo Local
```bash
npm install          # Instalar dependencias
npm start           # Ejecutar servidor de desarrollo (puerto 4200)
npm run watch       # Build en modo desarrollo con watch
```

### Producción
```bash
npm run build       # Build para producción
npm run vercel-build # Build específico para deployment en Vercel
```

## Configuración para Vercel

El proyecto está configurado para desplegarse automáticamente en Vercel con:

- **vercel.json**: Configuración de deployment para SPA
- **Build command**: `npm run vercel-build`
- **Output directory**: `dist/duodesign-landing`
- **Framework preset**: Angular

### Pasos para Deployment en Vercel

1. Conecta tu repositorio de GitHub con Vercel
2. Vercel detectará automáticamente que es un proyecto Angular
3. El build se ejecutará automáticamente con cada push a la rama principal
4. La aplicación estará disponible en la URL proporcionada por Vercel

## Características del Diseño

- **Responsive Design**: Adaptado para dispositivos móviles y desktop
- **Dark Mode Ready**: Configurado para modo oscuro
- **Smooth Scrolling**: Navegación suave entre secciones
- **Hover Effects**: Efectos interactivos en botones y elementos
- **Professional UI**: Colores corporativos y tipografía moderna

## Paleta de Colores

- **Primary**: #2B4C7E (azul corporativo)
- **Accent**: #D4A574 (dorado)
- **Background Light**: #F9FAFB
- **Background Dark**: #14181e
- **Dark Footer**: #1F2937

## Contacto

**Jose Martel** - Designer UI/UX  
WhatsApp: +56 9 5004 0166

**Brian Martel** - Fullstack Developer  
WhatsApp: +56 9 4433 6430

---

Desarrollado con ❤️ por los hermanos Martel