# TopAffiliates

Sitio web estático para presentar los programas de afiliados.

## Preparación para subir a SiteGround

1. Crea un nuevo repositorio en GitHub y sube este código.
2. En tu panel de SiteGround, ve a **Site Tools** y abre la sección **Devs > Git**.
3. Crea un repositorio de Git en SiteGround apuntando a `public_html` o al directorio donde deseas desplegar este sitio.
4. Obtén la URL remota de ese repositorio y añádela como `remote` en tu proyecto:
   ```bash
   git remote add siteground <URL_DEL_REPO_EN_SITEGROUND>
   ```
5. Envía el código a SiteGround con:
   ```bash
   git push siteground main
   ```
   Ajusta `main` si tu rama principal usa otro nombre.
6. Una vez hecho el push, SiteGround desplegará automáticamente los archivos en tu hosting.

Para actualizaciones futuras repite el paso 5 después de realizar cambios.
