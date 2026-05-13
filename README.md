# Ofertas Santa Rosa de Osos 🛒

Una plataforma web simple para comprar y vender productos en la comunidad de Santa Rosa de Osos.

## 🎯 Características

- **3 Categorías**: Productos de Segunda, Productos Nuevos y Servicios
- **Publicación de Productos**: Los usuarios pueden publicar productos con información completa
- **Expiración Automática**: Los posts se eliminan automáticamente después de 72 horas
- **Validación de Datos**: 
  - Precio mínimo (no permite $0, $111, $115)
  - Teléfono válido
  - Fotos obligatorias (máximo 5)
- **Galería de Imágenes**: Visualización de múltiples fotos por producto
- **Almacenamiento Local**: Los productos se guardan en el navegador

## 📋 Requisitos

No tiene requisitos. Es una aplicación web pura (HTML, CSS, JavaScript) que funciona en cualquier navegador moderno.

## 🚀 Cómo usar

1. Abre `index.html` en tu navegador
2. Selecciona una categoría (Productos de Segunda, Productos Nuevos o Servicios)
3. Haz clic en "+ Publicar" para crear un nuevo producto
4. Completa el formulario con:
   - Nombre del artículo
   - Características del producto
   - Precio (debe ser real, no 0, 111, 115)
   - Teléfono de contacto
   - Fotos del producto (máximo 5, máximo 5MB cada una)
5. ¡Publicado! Tu producto aparecerá en la categoría por 72 horas

## 📁 Estructura de archivos

```
Flasipromo/
├── index.html       # Estructura HTML
├── styles.css       # Estilos CSS
├── app.js          # Lógica JavaScript
└── README.md       # Este archivo
```

## 🎨 Diseño

- Interfaz moderna y responsiva
- Gradiente púrpura atractivo
- Navegación intuitiva
- Modal para ver detalles de productos
- Optimizado para dispositivos móviles

## 💾 Almacenamiento

Los productos se guardan en `localStorage` del navegador. Esto significa que:
- Los datos persisten si cierras y reabrís la página
- Los datos son locales de cada dispositivo/navegador
- Para compartir con más usuarios, considera usar una base de datos

## 🔒 Validaciones

- **Título**: Mínimo 3 caracteres
- **Descripción**: Mínimo 10 caracteres
- **Precio**: Debe ser mayor a 0 y no puede ser 0, 111, 115
- **Teléfono**: Mínimo 7 dígitos
- **Imágenes**: 1-5 archivos, máximo 5MB cada uno

## ⏰ Expiración

- Los productos expiran automáticamente después de 72 horas
- Se validan al cargar la página
- Se validan cada hora en segundo plano

## 🌐 Compatibilidad

Funciona en todos los navegadores modernos:
- Chrome
- Firefox
- Safari
- Edge

## 📝 Notas de desarrollo

Para mejorar en el futuro:
1. Integrar con backend (Node.js, Python, etc.)
2. Agregar base de datos (MongoDB, PostgreSQL, etc.)
3. Sistema de autenticación de usuarios
4. Búsqueda avanzada
5. Filtros por precio
6. Calificaciones y comentarios
7. Notificaciones por email

## 👨‍💻 Autor

Creado para la comunidad de Santa Rosa de Osos

## 📄 Licencia

MIT License - Libre para usar y modificar
