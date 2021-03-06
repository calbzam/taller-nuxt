# TODO taller

[x] Pantallazos 2018 en resumen: reducir tamaño

[x] Pasos instalación en README (algo similar a [Django Girls](https://tutorial.djangogirls.org/es/installation/) o [VueVixens](https://vuevixens.github.io/docs/workshop/ch1.html)):
- [x] Crear cuenta GitHub si no se tiene (para Codesandbox y para despliegue).
- [x] Opción 1: Descargar en local
    - [x] [Nuxt (node, npm, npx) en Mac, Windows y Linux](https://nuxtjs.org/guide/installation/).
    - [x] Vue Dev tools en Chrome.
    - [x] VS Code.
    - [x] Git.
- [x] Opción 2: Usar [Codesandbox](https://codesandbox.io/s/github/nuxt/codesandbox-nuxt)
- [x] Spotify API.

[x] Rama "nuxt0": Conectar con API Spotify para ver qué pantallas se podrían mostrar en la aplicación.
- [x] Crear un Client ID en el [Dashboard](https://developer.spotify.com/dashboard/applications):
    - App Name: Wecodefy
    - Description: Get your statistics from last year in a similar way as spotify wrappers.
    - What are you building? Website.
    - Are you developing a commercial integration? No
- [x] Get Top User artists: Se necesita [User Authorization](https://developer.spotify.com/documentation/general/guides/authorization-guide/): To get that authorization, your application generates a call to the Spotify Accounts Service /authorize endpoint, passing along a list of the scopes for which access permission is sought.
    - [Get User's Top Artists and Tracks](https://developer.spotify.com/console/get-current-user-top-artists-and-tracks/?type=artists&time_range=&limit=&offset=)
- [x] Implicit Grant: [Example](https://gist.github.com/igorPhelype/68239ecab9afcc50230ce0c61c3bac2f), [Authorization Guide](https://developer.spotify.com/documentation/general/guides/authorization-guide/).

[x] Rama en GitHub por cada funcionalidad de la aplicación (nuxt1, ...nuxtn):
- [x] Rama "nuxt1": Rama inicial con las dependencias necesarias para la aplicación.
- [x] Rama "nuxt2": Componentes y layout con parte estática. Global CSS (metodología BEM). Nuxt-link. Transición entre páginas. SEO y meta tags. Mostrar code-splitting.
    - [x] Imagen Wecodefy: Transparente.
    - [x] Prueba de estructura del layout.
    - [x] Global CSS.
    - [x] Header y footer con elementos opcionales: Crear cada página y añadir condiciones en el layout.
    - [x] Nuxt-link para moverse entre páginas (ver todos los botones)
    - [x] Separar TheFooter en 3 componentes para que el componente sea más entendible.
    - [x] Color por página (pasar a layout también)
    - [x] Maquetación de cada página con metodología BEM y usando Flexbox.
    - [x] Añadir SEO y meta tags.
    - [x] Probar los linters de JS y CSS. Comprobar que el indentado es siempre el mismo para HTML, CSS, JavaScript.

- [x] Rama "nuxt3: Spotify API. Usar object.freeze (vue tip).
    - [x] Artists y tracks en `my-music-1` y `my-music-2`.
    - [x] Top Genre en `my-music-2`: palabra más repetida.
    - [x] Imagen top artist.
    - [x] Refactor llamada spotify-api.
    - [x] Mejorar la carga de datos (sobre todo la carga de la imagen): Async data para recoger datos del API.
        - ¿Por qué al recargar ya no se pintan los datos? https://github.com/nuxt/nuxt.js/issues/1133
    - [x] Llamar a la api de Spotify (`medium_term` y `long_term`) en la home y guardar datos en Vuex para usarlo en cada página. Cuando se recarga se borran los datos también.
    - [x] A veces no cambia de página bien después de recargar

- [x] Rama "nuxt4":
    - [x] Ver código generado estático en dist con el pre rendering.
    - [x] Despliegue estático GitHub Pages.
    - [x] Añadir los redirects de la aplicación desplegada en Spotify Developers.
    - [x] Compartir en twitter `https://cristinafsanz.github.io/taller-nuxt/my-music-2`: Descubre tus artistas y canciones favoritos en WeCodefy.
        - Url la de la página del taller para que se anime la gente a hacerlo

- [x] Añadir versiones de node y npm y cómo lo instalé con Windows

- [x] Explicación Nuxt en README.

- [ ] Hacer la misma aplicación en Codesandbox para apuntar los pasos en README.

    - Crear cuenta en [CodeSandbox](https://codesandbox.io/) y hacer un fork de [codesandbox-nuxt](https://codesandbox.io/s/github/nuxt/codesandbox-nuxt), añadiendo las librerías que uso (spotify-api, eslint y push-dir).

- [ ] Revisar versión final del README de master y nuxt1, debería contener lo último con todos los enlaces de las instrucciones, junto con la última versión de la instalación (rama nuxtn).

## Días antes

- [ ] Cargar el ratón

- [ ] Pedir adaptador

- [ ] Documentación actualizada en todas las ramas

- [ ] Ensayo introducción y empezar a hacer la aplicación (bajando rama y en Codesandbox)

- [ ] Versión código y documentación en local del repo + en 1 usb + GitHub.

## Día antes

- [ ] Llevar mochila: ordenador + cargador + ratón + adaptador + pendrive

- [ ] Probar a poner en pantalla completa (Ctr + Cmd + F) + tamaño texto (Cmd+) + pantalla completa VS Code (Ctrl + B)

- [ ] Buscar colgantes de otras conferencias

## Día del taller

- [ ] Mutear ordenador

- [ ] Cargar ordenador durante el taller.
