# Compras Lovers - Sitio Web Estático

Este repositorio contiene la página web estática de **Compras Lovers**, lista para ser publicada en **GitHub Pages** de forma gratuita.

## Contenido del repositorio

- `index.html` → Página principal con cabecera, banner, productos destacados y pie de página.
- Imágenes de ejemplo están usando placeholders (`via.placeholder.com`). Se recomienda reemplazarlas por las imágenes reales de tus productos.

---

## Paso 1: Crear el repositorio en GitHub

1. Ingresa a [GitHub](https://github.com/) y crea una cuenta si no tienes.  
2. Haz clic en **New repository**.  
3. Nombre recomendado: `TU-USUARIO.github.io` (reemplaza `TU-USUARIO` por tu usuario de GitHub) para que la URL final sea `https://TU-USUARIO.github.io`.  
4. Marca **Public** y agrega un README si quieres.  

---

## Paso 2: Subir archivos

### Opción A: Desde la web de GitHub
1. Entra a tu repositorio.  
2. Haz clic en **Add file → Upload files**.  
3. Arrastra `index.html` y cualquier carpeta de imágenes que tengas.  
4. Haz **Commit changes**.

### Opción B: Usando Git (CLI)
```bash
# en la carpeta de tu proyecto
git init
git add .
git commit -m "Primer commit - Subida del sitio web"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main
