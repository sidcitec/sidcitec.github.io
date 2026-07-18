# SIDCITEC — sitio web Jekyll

Sitio institucional del grupo SIDCITEC, preparado para GitHub Pages.

## Editar contenido

- Configuración general: `_config.yml`
- Menú: `_data/navigation.yml`
- Miembros: `_data/members.yml`
- Proyectos: `_data/projects.yml`
- Servicios: `_data/services.yml`
- Página principal: `index.html`

## Ejecutar localmente

Requiere Ruby y Bundler:

```bash
bundle install
bundle exec jekyll serve --livereload
```

Abra `http://localhost:4000`.

## Publicar

Suba el contenido a la rama `main` del repositorio `sidcitec.github.io`. GitHub Pages compilará el sitio con la configuración incluida. En **Settings → Pages**, seleccione **Deploy from a branch**, rama `main` y carpeta `/ (root)`.

## Licencia

El diseño se basa en Hyperspace de HTML5 UP, distribuido bajo licencia Creative Commons Attribution 3.0. Consulte `LICENSE.txt`.

