# Preparación de GitHub Pages — sin despliegue

Objetivo: alojar únicamente documentos de privacidad ES/EN en este repositorio independiente. Esta preparación no autoriza publicar documentos ni activar Pages.

## Estado que debe conservarse

- Repositorio público independiente; ningún archivo de código, build, APK/AAB, respaldo o clave de la app.
- Settings > Pages sin fuente seleccionada (None/Disabled, según la interfaz). No guardar una fuente de publicación todavía.
- Sin workflow de despliegue activo, rama gh-pages, configuración DNS o dominio personalizado.
- Los HTML completos permanecen fuera de este repositorio público hasta autorización posterior.

preparation/pages-plan.json es documentación, no una configuración consumida por GitHub Pages.

## Estructura prevista para la publicación futura

Tras cerrar los pendientes y obtener autorización separada, colocar en la raíz únicamente los documentos finales privacy.es.html y privacy.en.html, con enlaces de idioma relativos que funcionen entre sí. La URL de cada política usará su nombre de archivo; no se presupone una página de inicio nueva.

URLs previstas, no verificadas ni activadas:

- https://amonterocabrera.github.io/rigelia-privacy/privacy.es.html
- https://amonterocabrera.github.io/rigelia-privacy/privacy.en.html

## Activación futura: no ejecutar ahora

1. Revisar textos finales, fecha de vigencia, alcance por países y prácticas de alojamiento. GitHub registra IP de visitantes por seguridad; conciliar la información del sitio antes de activarlo.
2. Obtener autorización expresa para publicar. Comparar los documentos con el contenido aprobado y revisar cualquier cambio. No publicar copias todavía marcadas como borrador.
3. Subir sólo los HTML finales de política a este repositorio. En Settings > Pages seleccionar la fuente acordada, por ejemplo main /root, y activar HTTPS cuando esté disponible. Ese paso sí publica una web.
4. Verificar respuesta HTTPS, ausencia de sesión y restricciones geográficas, enlaces ES/EN y acceso real desde la app. Una URL prevista no acredita ninguna de esas comprobaciones.

Documentación oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
HTTPS: https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https
Datos de visitas: https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
