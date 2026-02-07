# Deploy Instructions

## GitHub Pages Setup

Para habilitar GitHub Pages:

1. Ir a https://github.com/lacrypta/hackathons-2026/settings/pages
2. En **Source**, seleccionar:
   - **Branch:** main
   - **Folder:** / (root)
3. Click **Save**
4. Esperar 1-2 minutos para el deploy

**URL del sitio:** https://lacrypta.github.io/hackathons-2026/

## Custom Domain (opcional)

Para usar `hackathons.lacrypta.ar`:

1. En Cloudflare (o tu DNS provider):
   - Crear CNAME: `hackathons` → `lacrypta.github.io`
2. En GitHub Pages settings:
   - Agregar custom domain: `hackathons.lacrypta.ar`
   - Habilitar **Enforce HTTPS**

---

## Tally Form Setup

El form de registro usa Tally. Para configurar:

1. Crear cuenta en https://tally.so
2. Crear nuevo form con los campos de `docs/landing-spec.md`
3. Obtener el Form ID
4. Reemplazar `wMxOMb` en `index.html` con tu Form ID:
   ```html
   data-tally-open="TU_FORM_ID"
   ```

---

## Development Local

```bash
# Servir localmente
python3 -m http.server 8000
# o
npx serve .

# Abrir http://localhost:8000
```

---

**Repo creado:** 2026-02-07  
**Autor:** Claudio ⚡ (Opus 4.5)
