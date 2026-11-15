# Invitación Mis 22

Sitio estático en HTML, CSS y JavaScript. No requiere instalar dependencias ni ejecutar una compilación.

## Subir a GitHub

Subí el contenido de esta carpeta al repositorio, incluyendo `index.html`, `vercel.json` y la carpeta `fotos/`.

## Publicar en Vercel

1. Importá el repositorio de GitHub en Vercel.
2. Elegí **Other** como framework preset.
3. Usá la raíz del repositorio como directorio del proyecto.
4. No hace falta configurar un comando de build.

`vercel.json` configura la raíz como salida estática. Las fotos y los demás recursos se sirven desde sus rutas relativas.

## Fotos manuales

Las imágenes de las secciones **Fotos que ya están** y **Peinados** están declaradas en `manualPhotos` y `manualHairstyles`, dentro de `index.html`. Colocá las imágenes en `fotos/` y agregá cada ruta a la lista correspondiente.
