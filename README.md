# El Planeta de los Zafios · El videojuego

Plataformas a toda velocidad basado en el libro de humor **«El Planeta de los Zafios 1»** de **Marco Antonio Saborido Domínguez**. +18 · humor zafio.

## Jugar
- **En el navegador:** abre la web de GitHub Pages del repositorio (carpeta `docs/`). Desde Chrome en el móvil: menú ⋮ → «Instalar app».
- **Por WhatsApp:** `El_Planeta_de_los_Zafios.html` es el juego entero en un solo archivo.

## Carpetas
| Carpeta | Contenido |
|---|---|
| `docs/` | App web instalable (la publica GitHub Pages) |
| `android-proyecto/` | Proyecto Android (Capacitor) para APK / AAB |
| `play-store/` | Icono, gráfico destacado, capturas, ficha y privacidad |
| `.github/workflows/compilar-apk.yml` | Compila el APK automáticamente en GitHub |

## Sacar el APK
Pestaña **Actions** → «Compilar APK» → **Run workflow**. Al terminar (unos 5-8 min), abre la ejecución y descarga **Los-Zafios-APK** (es un .zip con el `app-debug.apk` dentro).

## Actualizar el juego
Sustituye el HTML en los tres sitios: `El_Planeta_de_los_Zafios.html`, `docs/index.html` (conservando las 3 líneas de manifest/iconos del `<head>`) y `android-proyecto/www/index.html` + `android-proyecto/android/app/src/main/assets/public/index.html`.

Personajes ficticios: cualquier parecido con la realidad será responsabilidad suya y de la persona que le suministra la sustancia.
