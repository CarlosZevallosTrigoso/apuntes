# apuntes: a favor y en contra de las imágenes

Un blog personal de reflexiones e ideas sobre las imágenes como fenómeno social, en relación a productos culturales y eventos del Perú y el mundo contemporáneo.

## Sobre el proyecto

Este espacio reúne textos que exploran ideas a partir de marcos semióticos y antropológicos. No buscan ser críticas formales, sino instancias de exploración y reflexión sobre el rol de las imágenes en nuestra sociedad contemporánea.

Los contenidos también forman parte del proceso de investigación doctoral del autor, sirviendo como espacio para articular y desarrollar ideas en curso.

## Autor

**Carlos Zevallos Trigoso**
- Doctorando en Antropología
- Antropólogo Visual y Comunicador por la PUCP
- Instagram: [@ca.zt](https://www.instagram.com/ca.zt/)
- Email: czevallost@rizoma.pe

## Relacionado

Este blog está vinculado a [Rizoma.pe](https://rizoma.pe/), una plataforma educativa que publica convocatorias a cursos sobre temas afines.

- Web: [rizoma.pe](https://rizoma.pe/)
- Instagram: [@rizoma.pe](https://www.instagram.com/rizoma.pe/)

## Estructura del proyecto

```
/
├── index.html              # Página principal del blog
├── info.html              # Información sobre el autor y el proyecto
├── css/
│   └── style.css          # Estilos del sitio
├── posts/
│   ├── template-post.html # Plantilla para nuevos posts
│   └── mi-primer-post.html # Posts individuales
└── README.md              # Este archivo
```

## Características técnicas

- **Sitio estático**: HTML, CSS y JavaScript vanilla
- **Tipografía**: Newsreader (Google Fonts) para una lectura cómoda
- **Responsive**: Adaptado para dispositivos móviles
- **Funcionalidad de ancho**: Los posts permiten alternar entre párrafos anchos y estrechos para mejorar la legibilidad

## Cómo agregar un nuevo post

1. **Copia el template**: Duplica `posts/template-post.html` con un nuevo nombre
2. **Actualiza los metadatos**:
   - Fecha de publicación
   - Número de palabras
   - Título del post
3. **Agrega el contenido**: Reemplaza el contenido de ejemplo con tu texto
4. **Actualiza el index**: Agrega una nueva entrada en `index.html`:
   ```html
   <div class="post-item">
       <span class="post-date">DD/MM/YYYY:</span>
       <a href="posts/tu-nuevo-post.html" class="post-link">Título del post</a>
   </div>
   ```
5. **Actualiza el contador**: Incrementa el número en `<span id="post-count">X</span>`

## Funcionalidades

### Toggle de ancho de párrafo
Cada post incluye un botón que permite alternar entre:
- **Párrafo ancho**: Ocupa todo el ancho disponible
- **Párrafo estrecho**: Limitado a 60% del ancho (máximo 700px) para mejor legibilidad en pantallas grandes

### Fecha automática
La página principal muestra automáticamente la fecha actual en español.

## Desarrollo local

Para trabajar con el sitio localmente:

1. Clona o descarga los archivos
2. Abre `index.html` en tu navegador
3. Para desarrollo, se recomienda usar un servidor local (ej: Live Server en VS Code)

## Contacto

Para consultas, comentarios o colaboraciones relacionadas con el contenido del blog:
**czevallost@rizoma.pe**
