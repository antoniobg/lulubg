# Sitio Web - Psiquiatría Perinatal

Un sitio web estático y profesional para una psiquiatra especializada en salud mental perinatal, diseñado con un enfoque limpio, moderno y cálido.

## 🌟 Características

- **Diseño Responsive**: Adaptable a todos los dispositivos (móvil, tablet, escritorio)
- **Navegación Intuitiva**: Menú hamburguesa en móvil, navegación clara en escritorio
- **Formulario de Contacto**: Integrado con Formspree para manejo de mensajes
- **Diseño Profesional**: Colores suaves y cálidos, tipografía legible
- **SEO Optimizado**: HTML semántico para mejor posicionamiento
- **Sin Dependencias**: Funciona sin necesidad de instalación o compilación

## 📋 Páginas Incluidas

1. **Inicio** (`index.html`)
   - Sección hero con presentación profesional
   - Servicios destacados
   - Llamadas a la acción claras

2. **Sobre mí** (`sobre-mi.html`)
   - Biografía profesional
   - Credenciales y formación
   - Servicios detallados (6 especialidades)

3. **Contacto** (`contacto.html`)
   - Información de contacto completa
   - Formulario funcional con validación
   - Manejo de errores y confirmaciones

## 🚀 Instalación y Uso

### Opción 1: GitHub Pages (Recomendado)
1. Haz fork de este repositorio o sube los archivos a tu propio repositorio
2. Ve a Settings > Pages en tu repositorio de GitHub
3. Selecciona "Deploy from a branch" y elige la rama `main`
4. Tu sitio estará disponible en `https://tu-usuario.github.io/nombre-repositorio/`

### Opción 2: Hosting Local
1. Descarga todos los archivos
2. Abre `index.html` en tu navegador web
3. ¡Listo! El sitio funcionará completamente

### Opción 3: Otros Servicios de Hosting
Este sitio es compatible con cualquier servicio de hosting estático:
- Netlify
- Vercel
- Firebase Hosting
- Surge.sh

## ⚙️ Personalización

### 1. Información Básica
Busca y reemplaza los siguientes marcadores en todos los archivos:

- `[Nombre Completo]` → Nombre real de la doctora
- `[email]@ejemplo.com` → Email real
- `+[Código de país] [Número de teléfono]` → Teléfono real
- `[Dirección completa del consultorio]` → Dirección real

### 2. Biografía y Servicios
En `sobre-mi.html`, actualiza:
- Biografía profesional
- Credenciales y formación
- Experiencia específica
- Descripción de servicios

### 3. Formulario de Contacto
En `contacto.html`, línea ~165:
```html
<form action="https://formspree.io/f/TU_FORM_ID" method="POST">
```
Reemplaza `TU_FORM_ID` con tu ID real de Formspree.

### 4. Foto Profesional
Reemplaza el placeholder de foto en `sobre-mi.html` con una imagen real:
```html
<!-- Buscar este div y reemplazar con tu foto -->
<div class="aspect-square max-w-md mx-auto bg-gradient-to-br from-pink-100 to-blue-100 rounded-2xl shadow-lg overflow-hidden">
    <img src="ruta-a-tu-foto.jpg" alt="Dra. Tu Nombre" class="w-full h-full object-cover">
</div>
```

### 5. Redes Sociales
Actualiza los enlaces en el footer de todas las páginas:
```html
<!-- Cambiar los href="#" por las URLs reales -->
<a href="https://facebook.com/tu-perfil" class="text-gray-400 hover:text-white transition-colors">
```

## 🎨 Personalización de Colores

El sitio usa una paleta de colores suaves. Para cambiar los colores, modifica la configuración de Tailwind en cada archivo HTML:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'soft-pink': '#fdf2f8',    // Rosa suave
                'warm-pink': '#fce7f3',    // Rosa cálido
                'sage': '#f0fdf4',         // Verde salvia
                'soft-blue': '#eff6ff'     // Azul suave
            }
        }
    }
}
```

## 📋 Configuración de Formspree

1. Ve a [formspree.io](https://formspree.io) y crea una cuenta
2. Crea un nuevo formulario
3. Copia el endpoint proporcionado
4. Reemplaza la URL en el atributo `action` del formulario en `contacto.html`

El formulario incluye:
- Validación de campos requeridos
- Manejo de respuestas de éxito/error
- Indicador de carga durante el envío
- Checkbox de política de privacidad

## 🔧 Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **TailwindCSS**: Framework CSS vía CDN
- **Vanilla JavaScript**: Interactividad mínima
- **Formspree**: Manejo de formularios
- **GitHub Pages**: Hosting gratuito

## 📱 Compatibilidad

- ✅ Chrome (últimas versiones)
- ✅ Firefox (últimas versiones)
- ✅ Safari (últimas versiones)
- ✅ Edge (últimas versiones)
- ✅ Navegadores móviles (iOS/Android)

## 🆘 Soporte

Si encuentras algún problema:

1. Revisa que todos los archivos estén en la carpeta raíz
2. Verifica que las URLs de navegación sean correctas
3. Comprueba que el endpoint de Formspree esté configurado
4. Asegúrate de que no hay errores en la consola del navegador

## 📄 Licencia

Este proyecto está diseñado para uso profesional en el ámbito de la salud mental. Puedes modificarlo y adaptarlo según tus necesidades.

---

*Desarrollado para proporcionar una presencia web profesional y accesible para especialistas en psiquiatría perinatal.*