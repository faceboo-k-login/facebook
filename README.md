# SocialLab - Proyecto escolar

Página de dos columnas, sin QR, inspirada en patrones visuales de redes sociales, con una marca propia.

## Uso
1. Abre esta carpeta en Visual Studio Code.
2. Abre `index.html` con la extensión Live Server.
3. Pulsa «Crear cuenta de demostración», introduce un usuario ficticio y una contraseña **que no uses en ninguna cuenta real**.
4. Vuelve al login y prueba el acceso.

## Fondo visual
`assets/bg.svg` es un fondo local ilustrado. Si tienes una foto propia o autorizada para usar, puedes guardarla como `assets/bg.jpg` y cambiar `url('../assets/bg.svg')` por `url('../assets/bg.jpg')` en `css/styles.css`.

## Publicación
Sube `index.html`, las carpetas `css`, `js`, `assets` a la raíz de un repositorio GitHub público. En Settings > Pages selecciona Deploy from a branch, `main`, `/ (root)`.
Tu URL normalmente será `https://TU-USUARIO.github.io/NOMBRE-REPOSITORIO/`.

## Seguridad y límites
La cuenta es una **simulación**, no autenticación segura. El navegador guarda únicamente el usuario y un hash SHA-256 de la contraseña de prueba en localStorage. SHA-256 sin sal no es adecuado para autenticar usuarios reales; ni el hash ni el código de validación son secretos frente a quien use el navegador. No uses datos reales. Las cuentas no se comparten entre dispositivos, no hay backend y no se capturan direcciones IP ni contraseñas reales. La página no suplanta Facebook y no oculta el destino del enlace.
