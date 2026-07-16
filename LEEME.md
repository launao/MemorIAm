# Cómo publicar este landing en GitHub Pages

Este paquete ya está listo para subir tal cual. Solo te faltan las 8 fotos (que no pude descargar yo mismo por una restricción de mi entorno) — bájalas tú con estos links directos y este landing queda funcionando al 100%, sin depender de nada externo.

## Paso 1 — Descarga las 8 fotos

Haz clic derecho en cada link → "Guardar imagen como..." → guárdala **exactamente con el nombre indicado** dentro de la carpeta `img/` de este mismo paquete (ya viene creada, vacía).

| Nombre de archivo (guárdalo así) | Link para descargar |
|---|---|
| `hero-boda.jpg` | https://d8j0ntlcm91z4.cloudfront.net/user_3FpiMQJpodBPIZfzW4BI5HX2udh/hf_20260716_192542_e7dfdfa3-26c5-43fd-a943-93efff399d84.png |
| `paso1-qr.jpg` | https://d8j0ntlcm91z4.cloudfront.net/user_3FpiMQJpodBPIZfzW4BI5HX2udh/hf_20260716_192555_5f15282d-d712-47aa-86ce-516377f9c41a.png |
| `paso2-baile.jpg` | https://d8j0ntlcm91z4.cloudfront.net/user_3FpiMQJpodBPIZfzW4BI5HX2udh/hf_20260716_192545_6b6aa368-3a29-42c8-9a32-a3afdc7dfd40.png |
| `paso3-mesa.jpg` | https://d8j0ntlcm91z4.cloudfront.net/user_3FpiMQJpodBPIZfzW4BI5HX2udh/hf_20260716_192557_2215e26c-8eed-4d39-a109-d5d792228024.png |
| `galeria-cumpleanos.jpg` | https://d8j0ntlcm91z4.cloudfront.net/user_3FpiMQJpodBPIZfzW4BI5HX2udh/hf_20260716_192549_e0fabd75-2919-40bb-86c2-1543ce43a922.png |
| `galeria-corporativo.jpg` | https://d8j0ntlcm91z4.cloudfront.net/user_3FpiMQJpodBPIZfzW4BI5HX2udh/hf_20260716_192551_56519f7a-955c-4ca0-b9b0-de1e6571fd20.png |
| `galeria-carrera.jpg` | https://d8j0ntlcm91z4.cloudfront.net/user_3FpiMQJpodBPIZfzW4BI5HX2udh/hf_20260716_192553_431f01a6-fcab-4360-aa57-39561ebfcc18.png |
| `galeria-fiesta.jpg` | https://d8j0ntlcm91z4.cloudfront.net/user_3FpiMQJpodBPIZfzW4BI5HX2udh/hf_20260716_192559_adbc2a27-44f8-4d7d-a168-4584e99a19d3.png |

> Ojo: aunque el link termina en `.png`, no importa que la guardes como `.jpg` — el HTML ya la busca con ese nombre exacto. Si algún archivo falta o el nombre no coincide, esa sección simplemente muestra el mosaico ilustrado de respaldo — nada se rompe.

## Paso 2 — Crea el repositorio en GitHub

1. Entra a **github.com/new**
2. Ponle un nombre, por ejemplo `memoria-landing`
3. Déjalo en **Public** (necesario para GitHub Pages gratis)
4. Dale a **Create repository** (no marques ninguna opción de inicializar con README)

## Paso 3 — Sube los archivos

1. En la página del repo recién creado, haz clic en **"uploading an existing file"**
2. Arrastra `index.html`, `LEEME.md`, y la carpeta `img` completa (con las 8 fotos ya adentro) a la zona de subida
3. Dale **Commit changes**

## Paso 4 — Activa GitHub Pages

1. Ve a **Settings → Pages** (menú de la izquierda)
2. En "Build and deployment", selecciona **Deploy from a branch**
3. Branch: **main**, carpeta: **/ (root)** → **Save**
4. Espera 1-2 minutos y arriba te va a aparecer la URL pública, algo como:
   `https://tu-usuario.github.io/memoria-landing/`

Listo — esa URL ya la puedes compartir con cualquiera, y las fotos van a cargar siempre porque es un servidor real, no un visor con restricciones.
