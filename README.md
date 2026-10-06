# Arqueo Poker

App para el arqueo de caja de los torneos de poker: entradas, fichas (bounty), entregas anticipadas, conteo de caja, cierre de fichas, cierre poker e historial de cierres.

Es un solo archivo (`index.html`). No necesita servidor ni instalación.

## Cómo publicarla en GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `arqueo-poker`).
2. Subí **todos** los archivos de la carpeta: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` y los íconos (`icon.svg`, `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`) (botón **Add file → Upload files**).
3. Entrá a **Settings → Pages**. En **Source** elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)` y tocá **Save**.
4. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/arqueo-poker/`.

## Instalarla como app (PWA)

- **PC (Chrome o Edge):** aparece el ícono de instalar en la barra de direcciones, o el botón **Instalar app** arriba en la página.
- **Android (Chrome):** menú ⋮ → **Instalar app** / **Agregar a la pantalla principal**.
- **iPhone (Safari):** botón Compartir → **Agregar a inicio**.

Una vez instalada funciona sin internet. Cuando subas una versión nueva a GitHub, la app la toma sola la próxima vez que se abra con conexión.

## Uso rápido

- **Arqueo:** valor de inscripción, anticipadas, inscripciones, recompras, cargo y fichas que quedan, y el conteo de caja (lo que hay ahora).
- **Entregas anticipadas:** armá la entrega y tocá **Registrar**. Los billetes se descuentan solos del conteo. Se puede imprimir o compartir (texto o imagen).
- **Cierre total:** cierre de fichas (se entrega aparte) y conciliación por billete, cada uno con su comprobante.
- **Cerrar arqueo:** guarda la noche en el **Historial** y ofrece imprimir o compartir.
- **Historial:** ver o reimprimir cierres anteriores, **Exportar a Excel** (.csv) y **Descargar / Restaurar copia de seguridad**.
- **Nuevo arqueo:** empieza una noche nueva. Mantiene el valor de inscripción y el cargo de fichas.
- **Clave** para *Ajustar tamaños*, *Anular* entregas y *Borrar* cierres del historial: 1318.

## Importante

- Los datos se guardan **en el navegador** donde se usa la app. Si se borran los datos del navegador o se usa otra computadora, no aparecen. Descargá una **copia de seguridad** cada tanto desde el Historial.
- La clave evita errores, pero no es una protección real: se puede leer en el código.
- Imprimir funciona abriendo la app en el navegador (Chrome, Edge, etc.).
