# Mis Finanzas — app para tu celular

## Contenido
| Archivo | Para qué sirve |
|---|---|
| index.html | La app completa |
| manifest.webmanifest | Nombre, ícono y colores al instalarla |
| sw.js | Permite abrirla sin internet |
| icons/ | Íconos para iPhone y Android |

## 1. Publicarla (una sola vez, gratis)
**Opción A: Netlify (la más fácil)**
1. Crea una cuenta gratuita en netlify.com.
2. En tu panel, elige la opción para publicar arrastrando una carpeta (deploy manually).
3. Arrastra la carpeta `mis-finanzas` completa, ya descomprimida.
4. Netlify te da una dirección tipo `https://nombre.netlify.app`. En la configuración del sitio puedes cambiar el nombre.

**Opción B: GitHub Pages**
1. Crea una cuenta en github.com y un repositorio nuevo.
2. Sube todos los archivos de la carpeta (Add file → Upload files).
3. Settings → Pages → Deploy from a branch → `main` → Save.

La dirección debe empezar con **https**; si no, no se puede instalar.

## 2. Instalarla en el celular
- **iPhone:** abre la dirección en **Safari** → botón Compartir → **Agregar a pantalla de inicio**.
- **Android:** abre la dirección en **Chrome** → menú ⋮ → **Instalar app**.

Después ábrela siempre desde el ícono, no desde el navegador: la app instalada guarda sus datos por separado.

## 3. Tus datos
- Se guardan solo en tu celular. Nadie más puede verlos, tampoco el sitio donde la publicaste.
- Si borras la app o cambias de teléfono, se pierden. Usa **Exportar respaldo (.json)** una vez al mes y guárdalo en iCloud, Drive o WhatsApp. La app te lo recuerda cada 30 días.
- Para pasar tus datos a otro teléfono: instala la app ahí y usa **Importar respaldo**.

## 4. Actualizar la app
Sube el nuevo `index.html` y en `sw.js` cambia `VERSION = "v1"` por `"v2"`. La próxima vez que abras la app con internet se actualiza sola y tus datos se conservan.
