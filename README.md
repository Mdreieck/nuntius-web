# nuntius-web

Sitio público de la **app móvil Nuntius** (MDreieck, S.A. de C.V.): presentación de la
aplicación y **aviso de privacidad**.

- `index.html` — landing de la app.
- `privacidad.html` — aviso de privacidad. **Google Play exige esta URL pública** en la ficha
  de la aplicación, así que no se mueve ni se renombra sin actualizarla también allá.
- `capturas/` — capturas de la app. NO se toman a mano: las genera
  `flutter test --update-goldens test/play_screenshots_test.dart` en el repo `nuntius`, con los
  widgets de producción y datos de ejemplo (sin datos de personal real).

Se publica con **GitHub Pages** desde `main`: <https://mdreieck.github.io/nuntius-web/>

Desarrollado por Irving Guerra.
