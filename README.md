# CanvaWebsite

Sitio web estático en **HTML + JavaScript** pensado para publicarse en **GitHub Pages** (con dominio propio mediante `CNAME`). El repositorio incluye la página principal, carpetas de assets y un `sitemap.xml` básico para SEO.

---

## 📁 Estructura


├─ index.html # Página principal
├─ sitemap.xml # Mapa del sitio (SEO)
├─ CNAME # Dominio personalizado de GitHub Pages
├─ images/ # Imágenes y favicons
├─ fonts/ # Tipografías web (opcional)
├─ js/ # Scripts JS (opcional)
└─ AGENTS.md # Notas internas / documentación auxiliar

> **Tecnologías:** HTML (≈99.8%) y un pequeño porcentaje de JavaScript.

---

## 🚀 Cómo ejecutarlo en local

No requiere build ni dependencias.

**Opción A (rápida):** abrir `index.html` directamente en el navegador.  
**Opción B (servidor local recomendado):**
```bash```
# con Python 3
python3 -m http.server 8000
# luego visitar http://localhost:8000


🌐 Deploy en GitHub Pages
Hacé push a la rama main.
En Settings → Pages:
Source: Deploy from a branch
Branch: main y carpeta /root.
(Opcional) Dominio propio:
Mantené el archivo CNAME en la raíz con tu dominio.
Configurá los registros DNS del dominio para GitHub Pages (CNAME a <usuario>.github.io o A/AAAA según proveedor).
En Settings → Pages, activá Enforce HTTPS cuando esté disponible.
URL por defecto (si no usás dominio propio):
https://<tu-usuario>.github.io/CanvaWebsite/
✏️ Personalización
Contenido: editar textos, títulos y metatags en index.html.
Imágenes: reemplazar archivos en images/ (respetar nombres o actualizar rutas).
Fuentes: agregar/quitar tipografías en fonts/ y referenciarlas desde el <head>.
Scripts: añadir funcionalidades en js/ y enlazarlas en el HTML.
Favicon / Open Graph: actualizar íconos y metadatos sociales en el <head>.
🔎 SEO básico
Metadatos: title, meta description, og:*, twitter:* en index.html.
Sitemap: mantener URLs correctas en sitemap.xml.
(Opcional) robots.txt: agregar si necesitás controlar el indexado.
♿ Accesibilidad (recomendado)
Usar texto alternativo en imágenes (alt).
Mantener jerarquía de encabezados (h1 → h2 → h3).
Contraste adecuado y foco visible para elementos interactivos.
🧪 Checklist antes de publicar
 Links internos y externos funcionando.
 Metas y favicon actualizados.
 sitemap.xml apunta a la URL final (dominio propio o GitHub Pages).
 Prueba en móvil y escritorio.
🤝 Contribuir
Hacé un fork del repositorio.
Creá una rama: git checkout -b feature/mi-mejora.
Commit: git commit -m "Agrega <mi-mejora>".
Push: git push origin feature/mi-mejora.
Abrí un Pull Request.
📜 Licencia
Aún no se especifica una licencia. Si el proyecto es open source, se recomienda agregar un archivo LICENSE (por ejemplo, MIT). Si es privado/propietario, documentalo aquí.
