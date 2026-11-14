# jotade-web

Web de Jotade, publicada con GitHub Pages.

## Archivos con URL fija

Estas rutas se usan fuera de la web (firma de correo, iconos). No las renombres ni las muevas:

| Ruta | Uso |
| --- | --- |
| `/logo-firma.png` | Logo de la firma anterior. Se mantiene para que los correos ya enviados sigan mostrándolo |
| `/firma-v2.png` | Logo de la firma nueva (144×144, se muestra a 48 px) |
| `/favicon.ico`, `/favicon.svg` | Favicon |
| `/apple-touch-icon.png` | Icono al guardar la web en iPhone |
| `/site.webmanifest`, `/android-chrome-*.png` | Icono en Android |
| `/assets/marca/` | Logos de la marca, incluido el logo animado |

## Dominio propio

Cuando `jotade.io` apunte a GitHub Pages, añade el dominio en Settings → Pages. GitHub creará el archivo `CNAME`. No lo crees antes de configurar el DNS: la web dejaría de cargar en la URL de github.io.
