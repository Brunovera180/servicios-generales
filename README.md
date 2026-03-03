# Servicios Generales - Sitio Web

Sitio web estático para servicios generales con especialización en instalaciones de cámaras de seguridad para hogares y oficinas.

## 🚀 Características

- **Diseño Responsive**: Adaptable a todos los dispositivos (móvil, tablet, desktop)
- **Moderno**: Interfaz limpia y profesional con animaciones suaves
- **SEO Optimizado**: Meta tags y estructura semántica HTML5
- **Formulario de Contacto**: Con validación en tiempo real
- **Navegación Suave**: Scroll animado entre secciones
- **Performance**: Código optimizado y lazy loading

## 📁 Estructura del Proyecto

```
servicios-generales/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidad JavaScript
└── README.md           # Este archivo
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Diseño moderno con Grid y Flexbox
- **JavaScript ES6+**: Interactividad y validaciones
- **Google Fonts**: Tipografía Inter

## 🌐 Despliegue

### GitHub Pages

1. Sube los archivos a tu repositorio GitHub
2. Ve a Settings > Pages
3. Selecciona la rama `main` y carpeta `/root`
4. Tu sitio estará disponible en `https://[username].github.io/servicios-generales`

### Cloudflare Pages

1. Conecta tu repositorio de GitHub a Cloudflare Pages
2. Configura el build preset `Static HTML`
3. Directorio de salida: `.` (raíz)
4. Deploy automático en cada push

### Netlify

1. Arrastra la carpeta del proyecto a netlify.com
2. O conecta tu repositorio GitHub
3. Deploy automático configurado

## 📱 Secciones del Sitio

1. **Hero**: Presentación principal con llamada a la acción
2. **Servicios**: Grid de servicios principales
   - Cámaras de Seguridad
   - Mantenimiento del Hogar  
   - Servicios para Oficinas
3. **Seguridad**: Detalles específicos de cámaras de seguridad
4. **Contacto**: Formulario funcional con validación
5. **Footer**: Información de contacto y enlaces

## 🎨 Personalización

### Cambiar Colores
Edita las variables CSS en `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Azul principal */
    --accent-color: #f59e0b;      /* Naranja acento */
    --text-dark: #1f2937;        /* Texto oscuro */
}
```

### Actualizar Contacto
Modifica los datos en `index.html`:
- Teléfono: Línea 145
- Email: Línea 148
- Ubicación: Línea 151

### Agregar Servicios
Edita las cards en la sección `.services-grid` en `index.html`.

## 📊 Formulario de Contacto

El formulario incluye:
- Validación en tiempo real
- Formato automático de teléfono argentino
- Notificaciones de éxito/error
- Diseño responsive

**Nota**: El formulario actualmente simula el envío. Para integración real:
1. Configura un backend (Node.js, PHP, etc.)
2. O usa servicios como Formspree, Netlify Forms
3. O integra con EmailJS

## 🔧 Optimización

- **Minificación**: Comprime CSS y JS para producción
- **Imágenes**: Usa WebP y lazy loading
- **CDN**: Considera CDN para fuentes y assets
- **Cache**: Configura headers de cache adecuados

## 📈 SEO

- Meta tags optimizados
- Estructura semántica HTML5
- URLs amigables
- Open Graph tags para redes sociales

## 🤝 Contribuir

1. Fork del proyecto
2. Crear rama feature/nueva-funcionalidad
3. Commit de cambios
4. Push a la rama
5. Pull Request

## 📄 Licencia

Este proyecto es de código abierto bajo la Licencia MIT.

---

**Creado con ❤️ para Servicios Generales**