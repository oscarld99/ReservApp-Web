# ReservApp — Sitio Web Oficial

Sitio web y documentación legal de **ReservApp**, la app para reservar escenarios deportivos en el Atlántico, Colombia.

🌐 **URL:** https://oscarld99.github.io/ReservApp-Web/

---

## Estructura

```
/
├── index.html                      # Landing page principal
├── screens/                        # Imágenes y screenshots
│   ├── screenshot-home.png
│   ├── screenshot-map.png
│   ├── screenshot-booking.png
│   ├── screenshot-admin.png
│   ├── favicon.png
│   └── og-image.png                # Imagen para redes sociales (1200×630)
└── docs/                           # Documentos legales
    ├── politica-privacidad.md      # Política de Privacidad (Ley 1581/2012)
    ├── terminos-condiciones.md     # Términos y Condiciones de Uso
    └── politica-cookies.md         # Política de Cookies y Almacenamiento
```

---

## Cómo actualizar el sitio

Este sitio usa **GitHub Pages**. Cualquier push a la rama `main` actualiza el sitio automáticamente.

### Agregar screenshots reales

1. Toma capturas de pantalla de la app en el simulador o dispositivo físico.
2. Guárdalas en la carpeta `screens/` con los nombres indicados arriba.
3. En `index.html`, reemplaza cada bloque `<div class="screenshot-slot">` por:
   ```html
   <img src="screens/screenshot-home.png" alt="Home ReservApp" style="border-radius:24px;" />
   ```
4. Haz commit y push — GitHub Pages publica en segundos.

### Agregar links de Play Store / App Store

Cuando la app esté publicada en las tiendas, actualiza en `index.html` la sección `#descargar`:
- Reemplaza los `<span class="store-btn">` deshabilitados por `<a href="URL_TIENDA">`.

### Actualizar documentos legales

Edita los archivos `.md` correspondientes y actualiza la fecha de versión en el encabezado.

---

## URLs de documentos legales

Estas URLs se usan en las fichas de Google Play y App Store:

| Documento | URL |
|---|---|
| Política de Privacidad | https://oscarld99.github.io/ReservApp-Web/docs/politica-privacidad |
| Términos y Condiciones | https://oscarld99.github.io/ReservApp-Web/docs/terminos-condiciones |
| Política de Cookies | https://oscarld99.github.io/ReservApp-Web/docs/politica-cookies |

---

## Contacto

Oscar David Lora De Sales — oscardavidloradesales@gmail.com
