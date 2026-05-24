# Gradiente Descendiente | Inteligencia Artificial

Este paquete contiene una página web estática lista para publicar en GitHub Pages.

## Archivos principales

- `index.html`: página web principal.
- `afiche_gradiente_descendiente.svg`: afiche editable/descargable.
- `mapa_mental_gradiente_descendiente.mmd`: mapa mental en Mermaid.
- `guion_sustentacion_10min.md`: guion para exposición de 10 minutos.
- `prompt_canva_afiche.txt`: prompt para generar o mejorar el afiche en Canva.
- `contenido_base.md`: contenido académico base.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo: `gradiente-descendiente-ia`.
2. Sube todos estos archivos al repositorio.
3. En GitHub, entra a **Settings > Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. En **Branch**, elige `main` y la carpeta `/root`.
6. Guarda. El enlace aparecerá como:
   `https://TU_USUARIO.github.io/gradiente-descendiente-ia/`

## Publicación por terminal

```bash
mkdir gradiente-descendiente-ia
cd gradiente-descendiente-ia

# Copia aquí los archivos del paquete

git init
git add .
git commit -m "Publica página sobre gradiente descendiente"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/gradiente-descendiente-ia.git
git push -u origin main
```

Después activa GitHub Pages desde **Settings > Pages**.

> Recomendación de seguridad: no pegues tokens dentro de archivos, repositorios, capturas ni chats públicos. Si un token fue compartido, revócalo y crea uno nuevo.