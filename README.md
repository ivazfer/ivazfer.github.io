# ivazfer.github.io

Portfolio de prácticas del ciclo, organizado por asignatura. Sitio estático con Jekyll, publicado con GitHub Pages (build automático, sin pasos manuales).

## Cómo añadir una práctica nueva

1. Exporta la página desde Notion como Markdown (te descarga un `.md` y una carpeta con las imágenes).
2. Copia ambos, tal cual salen de Notion, dentro de `inbox/<asignatura>/`. Carpetas disponibles:
   - `inbox/seguridad-alta-disponibilidad/`
   - `inbox/implantacion-aplicaciones-web/`
   - `inbox/administracion-sistemas-operativos/`
   - `inbox/proyecto-intermodular/`
   - `inbox/infraestructura-virtual/`
   - `inbox/administracion-base-datos/`
   - `inbox/servicios-red-internet/`
3. Dile a Claude: "publica la práctica de [tema] en [asignatura]".

Claude se encarga de: generar una descripción breve, detectar las habilidades/tecnologías tratadas, integrar la práctica en la web con las imágenes correctamente enlazadas, y hacer commit + push. GitHub Pages recompila solo en 1-2 minutos.

No hace falta tocar nada de `_layouts/`, `_data/` ni el resto de la estructura del sitio.
