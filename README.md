# Mondo Incredibile 3D — web pública para Google OAuth

Dos páginas HTML estáticas en italiano. Sitio diseñado para GitHub Pages **sin instalar nada**.

## URL gratuitas previstas (NO activas hasta publicar)
- Inicio: https://brianjara1996.github.io/
- Privacidad: https://brianjara1996.github.io/privacy.html
- Términos de uso: https://brianjara1996.github.io/#termini

## Pasos para publicar
1. Entrá con tu cuenta `brianjara1996` a https://github.com/new.
2. Creá un repositorio **público** llamado exactamente `brianjara1996.github.io` (habilitá README opcionalmente).
3. Subí a la raíz `index.html`, `privacy.html`, `style.css` y `.nojekyll` de esta carpeta. **Nunca** subas `.env`, claves, `client_secret.json`, `youtube_token.json`, videos o la base de datos de la oficina.
4. En el repositorio, `Settings > Pages > Build and deployment > Source: Deploy from a branch > main / (root) > Save`.
5. Abrí las URLs anteriores en una ventana privada. Puede tardar varios minutos.
6. Para Google Cloud, verificá el control del sitio en https://search.google.com/search-console (propiedad de prefijo URL `https://brianjara1996.github.io/`; método de archivo HTML de verificación de Google en la raíz del repo). Google puede pedir verificar también el dominio autorizado y/o otros requisitos. No garantizamos aprobación automática.
7. Google Auth Platform > Branding: Home page URL `https://brianjara1996.github.io/`, Privacy URL `https://brianjara1996.github.io/privacy.html`, Terms URL `https://brianjara1996.github.io/#termini` (o en blanco si Google lo permite), Authorized domain `brianjara1996.github.io` si se acepta como dominio registrable verificable.
8. Guardá. Volvé a `Pubblico > Pubblica app` y seguí los pasos que Google requiera.

## Datos a confirmar ANTES de publicarlas
- La dirección de contacto `brianjaras1996@gmail.com` proviene de la captura de Google Cloud. **Aparecerá públicamente** en la web. Cambiala antes de publicar si preferís otra dirección.
- Releé la política para confirmar que refleja el comportamiento real de tu oficina V6. No es asesoramiento legal.
- No dependas de que Google acepte un subdominio github.io sin verificarlo; las reglas de Google requieren dominio verificado.

Este repo debe contener solo los archivos estáticos de la web informativa. No aloja el software real, el backend ni credenciales.
