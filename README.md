# Libro web con Quarto (plantilla)

## Pasos rápidos
1. Crea un repositorio público en GitHub llamado `orientacion-educativa-libro`.
2. Sube todos los archivos de esta carpeta al repositorio.
3. Ve a **Settings → Pages** y elige **Deploy from a branch** con `gh-pages` (se creará con la acción).
4. Haz un commit (por ejemplo, edita `index.qmd`) y espera a que termine el workflow **Quarto Publish**.
5. Tu libro quedará publicado en `https://Samigabacho.github.io/orientacion-educativa-libro`.

## Editar contenido
- Pega el texto completo de tus unidades en `unidades/01-unidad1.qmd`, `02-unidad2.qmd`, `03-unidad3.qmd`.
- Añade referencias en `referencias.bib` y cita con `[@AutorAño]`.
- Coloca figuras en `fig/` y referencia con `![Título](fig/archivo.png){#fig-id}`.