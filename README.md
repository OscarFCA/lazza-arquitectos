# LAZZA Arquitectos — Landing

Landing page estática de **LAZZA Arquitectos**, estudio de arquitectura e interiorismo en Ciudad de México (desde 1997).

🔗 **En vivo:** https://oscarfca.github.io/lazza-arquitectos/

## Características

- Sitio 100% estático (HTML/CSS/JS vanilla) — sin dependencias ni build.
- Bilingüe **ES / EN** con toggle en la navegación.
- Contacto vía **WhatsApp** (botones + formulario que abre WhatsApp con el mensaje pre-armado).
- Imágenes optimizadas en **WebP** (de ~25 MB a ~2 MB).
- Responsive y respeta `prefers-reduced-motion`.

## Estructura

```
index.html        Página única, autocontenida (estilos + i18n + lógica inline)
assets/           Imágenes en WebP
.nojekyll         Sirve los archivos tal cual en GitHub Pages
```

## Configuración

El número de WhatsApp se define al inicio del `<script>` en `index.html`:

```js
var WA_NUMBER = "525621545400"; // +52 56 2154 5400
```

## Desarrollo local

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

---

Diseño basado en la identidad visual de lazza.com.mx.
