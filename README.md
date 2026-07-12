# LicitIA · Calculadora de valoración SaaS

Aplicación web educativa para estimar la valoración de una startup SaaS mediante el **método First Chicago**.

## Funciones

- Escenarios optimista, base y conservador.
- Probabilidades y valor presente ponderado.
- Valoración pre-money y post-money.
- Estimación de participación del inversionista.
- Referencias de múltiplos SaaS.
- Guardado local de ejercicios en el navegador.
- Reporte imprimible o guardable como PDF.

## Publicación con GitHub Pages

1. Crea un repositorio público en GitHub.
2. Sube `index.html`, `.nojekyll` y este `README.md` a la raíz.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`.
6. Guarda los cambios.

La dirección tendrá una estructura similar a:

`https://USUARIO.github.io/REPOSITORIO/`

## Requisitos y arquitectura

La aplicación no necesita servidor, base de datos ni proceso de compilación. React, ReactDOM, Babel y las fuentes se cargan desde servicios externos, por lo que la primera carga requiere conexión a internet.

Los ejercicios guardados permanecen únicamente en `localStorage` del navegador del usuario.

## Aviso

Herramienta con fines educativos e informativos. Los resultados dependen de los supuestos capturados y no constituyen asesoría financiera, legal ni de inversión.

© LicitIA Labs
