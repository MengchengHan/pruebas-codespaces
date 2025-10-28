# pruebas-codespaces

Proyecto de ejemplo con páginas HTML, CSS y JS.

Contenido relevante:
- `index.html` — página principal (usa `styles.css` y `script.js`).
- `about.html` — segunda página de ejemplo (usa `about.css` y `about.js`).
- `styles.css` — estilos base y variables para tema claro/oscuro.
- `script.js` — comportamiento global (toggle tema, smooth scroll, formulario simulado).

Cómo probar localmente:

1. Abrir `index.html` directamente en el navegador.
2. O servir el directorio con un servidor estático (recomendado para rutas relativas):

```bash
python3 -m http.server 8000
# luego abrir http://localhost:8000
```

Notas:
- `about.html` muestra cómo añadir páginas adicionales y ficheros JS/CSS específicos por página.
- Los ficheros JS usan APIs del navegador simples y no requieren instalaciones.
