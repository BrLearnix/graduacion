# Invitación a la Graduación — Sitio estático

Página estática generada para una invitación de graduación, creada con HTML y Tailwind (CDN).

Cómo usar:

- Abrir el archivo `index.html` en un navegador moderno.
- Para cambiar la fecha de la graduación, editar la variable `targetDate` en la parte inferior de `index.html`.
- Reemplazar las imágenes de muestra por las de la universidad en la carpeta deseada y actualizar las rutas en `index.html`.

Prueba local (opcional):

1. En Windows, desde PowerShell o CMD, ejecutar:

```bash
# Si tu navegador soporta abrir archivos locales, basta con:
start index.html

# O servir con un servidor simple (requiere Python instalado):
python -m http.server 8000
# luego abrir http://localhost:8000/index.html
```

Personalización rápida:

- `title`: cambiar el título en el `<head>`.
- `targetDate`: modificar la fecha objetivo en UNIX Date constructor (año, mes-1, día,...).
- Colores: editar las variables CSS en la sección `<style>`.

Si quieres, puedo:

- Añadir un formulario real de RSVP que guarde datos.
- Generar imágenes y recursos optimizados.
- Convertir esto en una página responsiva más avanzada con soporte multilenguaje.
