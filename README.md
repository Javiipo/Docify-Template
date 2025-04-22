# Plantilla Modular para Documentación de Plugins de Minecraft

Esta plantilla está diseñada para crear documentación moderna, limpia y fácil de entender para plugins de Minecraft. La estructura modular permite una personalización sencilla y rápida.

## Estructura de Archivos

```
/
├── index.html                # Página principal
├── pages/                    # Páginas adicionales
│   ├── commands.html         # Documentación de comandos
│   ├── permissions.html      # Documentación de permisos
│   ├── config.html           # Documentación de configuración
│   └── api.html              # Documentación de API (si aplica)
├── assets/
│   ├── css/
│   │   ├── main.css          # Estilos principales
│   │   ├── variables.css     # Variables CSS para personalización
│   │   ├── components/
│   │   │   ├── header.css    # Estilos del encabezado
│   │   │   ├── nav.css       # Estilos de navegación
│   │   │   ├── footer.css    # Estilos del pie de página
│   │   │   ├── cards.css     # Estilos para tarjetas
│   │   │   └── code.css      # Estilos para bloques de código
│   ├── js/
│   │   └── main.js           # JavaScript principal
│   └── img/                  # Imágenes del plugin
└── README.md                 # Este archivo
```

## Personalización

### 1. Información del Plugin

Edita los siguientes archivos para actualizar la información de tu plugin:

- `index.html`: Título, descripción y características principales
- `pages/*.html`: Contenido específico de cada sección

### 2. Estilos y Temas

Para personalizar la apariencia:

1. Modifica `assets/css/variables.css` para cambiar:
   - Esquema de colores
   - Tipografía
   - Espaciado
   - Bordes y radios

2. Los componentes individuales pueden personalizarse en sus respectivos archivos CSS en la carpeta `assets/css/components/`.

### 3. Personalización Avanzada

- Agrega nuevas páginas copiando y modificando las plantillas existentes en `pages/`
- Crea nuevos componentes CSS para funcionalidades específicas
- Personaliza el JavaScript en `assets/js/main.js` para añadir interactividad

## Instrucciones de Uso

1. Clona este repositorio o descarga los archivos
2. Reemplaza el contenido de ejemplo con la información de tu plugin
3. Personaliza los estilos según tus preferencias
4. Sube a GitHub Pages u otro servicio de hosting

## Recomendaciones

- Mantén la documentación clara y concisa
- Incluye ejemplos de código cuando sea posible
- Usa imágenes para mostrar características visuales
- Mantén actualizada la documentación con cada versión de tu plugin

## Licencia

Esta plantilla es de uso libre bajo la licencia MIT. Puedes usarla, modificarla y distribuirla como desees. Se agradece pero no es obligatorio incluir un enlace a este repositorio original.
