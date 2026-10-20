# Día de Compra

Descubre qué día comprar con tu tarjeta de crédito para tener más días para pagar, y con cuál de tus tarjetas te conviene pagar hoy.

- Registra cada tarjeta con su día de corte y su día de pago.
- Mira tu ciclo en un anillo de colores: ventana ideal, buen momento, regular y días a evitar.
- Compara tus tarjetas en "¿Con cuál pago hoy?".

## Privacidad

Las tarjetas se guardan solo en el navegador de cada persona (localStorage). No hay servidor, cuentas ni base de datos: nadie más puede ver tus datos. Solo se guardan el nombre que le pones a la tarjeta y los dos días; nunca el número de la tarjeta.

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La app completa |
| `manifest.webmanifest` | Permite instalarla como app en el teléfono |
| `apple-touch-icon.png` | Ícono en la pantalla de inicio del iPhone |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Íconos para Android y navegadores |

## Publicarla en GitHub Pages

1. Entra a github.com y crea un repositorio nuevo, público, por ejemplo `dia-de-compra`.
2. Toca **Add file → Upload files** y arrastra todos los archivos de esta carpeta (no la carpeta, sino su contenido). Toca **Commit changes**.
3. Ve a **Settings → Pages**. En **Branch** elige `main` y la carpeta `/ (root)`. Toca **Save**.
4. Espera uno o dos minutos. Tu app quedará en `https://TU-USUARIO.github.io/dia-de-compra/`.

Para actualizarla, sube el nuevo `index.html` al mismo repositorio; los cambios aparecen en uno o dos minutos.

## Tenerla como app en el teléfono

- **iPhone:** abre el enlace en Safari, toca Compartir y elige "Agregar a pantalla de inicio".
- **Android:** abre el enlace en Chrome, abre el menú y elige "Agregar a la pantalla principal" o "Instalar app".

Los cálculos son referenciales y asumen compras en una sola cuota. No es asesoría financiera.
