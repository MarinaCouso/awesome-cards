# Awesome Profile Cards :information_desk_person:

Aplicación para crear tarjetas de contacto personalizables, web refactorizada partiendo de ![este proyecto] (https://github.com/Adalab/project-promo-i-module-2-team-2-morning)desarrollado en javascript . Gracias a esta aplicación, podrás crear una tarjeta personalizada con tus datos personales, tus datos de contacto, tu imagen y además, podrás compartirla en Twitter de forma directa!

---

## Guía de inicio rápido

Este proyecto ha sido creado con [Adalab We Starter Kit](https://github.com/Adalab/Adalab-web-starter-kit).

Necesitarás instalar [Node.js](https://nodejs.org/) y [Gulp](https://gulpjs.com) para trabajar con este Starter Kit, luego:

1. Descarga o clona el repositorio
2. Instala las dependencias locales con `npm install`
3. Arranca el kit con `gulp`

## Espera, ¿esto se hace siempre?

> ### Solo una vez al principio en cada ordenador que utilicemos:

- Instalamos node
- Instalamos el comando de gulp de forma global para poder usarlo desde cualquier carpeta usando `npm install --global gulp-cli`

> ### Cada vez que descarguemos o clonemos un repo:

- `npm install` para instalar los paquetes necesarios para convertir Sass a CSS, minizarlo, etc.

> ### Cada vez que estemos trabajando con nuestro código:

- Desde nuestra terminal, ejecutamos el comando `gulp` para que realice la tarea por defecto, que en el caso del `gulpfile.js` que tenemos en adalab-web-starter-kit estará pendiente de nuestros archivos Sass, html y JavaScript y los compilará, minificará y/o recargará el servidor cada vez que hagamos un cambio

## Tareas de gulp incluidas

### Inicio de un web server para desarrollo

```
npm start
```

o lo que en este proyecto es lo mismo:

```
gulp
```

Lanza un webserver con BrowserSync y varios watchers estarán pendientes de los archivos SCSS/JS/HTML, en la carpeta **public/**, para recargar el navegador cuando se necesite.

### Versión lista para subir a producción

Para generar los ficheros para producción ejecuta:

```
npm run docs
```

o lo que en este proyecto es lo mismo:

```
gulp docs
```

En la carpeta **docs/** se generarán los CSS y JS minimizados y sin sourcemaps listos para subir al repo. A continuación súbelos al repo y activa en GitHub Pages la opción **master/docs/**, para que GitHub Pages sirva la página desde la carpeta **docs/**.

---

Si quieres generar los ficheros listos para producción y además subirlos a GitHub directamente ejecuta el siguiente comando:

```
npm run push-docs
```

Este comando borra la carpeta **docs/**, la vuelve a generar, crea un commit con los nuevos ficheros y hace un `git push`, todo del tirón. ¿Cómo se te queda el cuerpo?. Si quieres saber cómo funciona échale un ojo al fichero `package.json`.

## Construido con :hammer_and_wrench:

1. **Visual Studio Code** - Editor de código.
2. **Javascript** - Lenguaje de programación.
3. **Git** - Para el control de versiones.
4. **Github** - Como repositorio remoto.
5. **Github Pages** - Para su publicación.
6. **SASS** - Para añadir estilos.

---

## Otras fuentes :wrench:

1. [Awesome Cards](https://us-central1-awesome-cards-cf6f0.cloudfunctions.net/) - Para crear las tarjetas de contacto.
2. [Fontawesome](https://fontawesome.com/) - Para obtener iconos utilizados en diferentes componentes.

---

## Equipo de desarrollo :fountain_pen:

[Margarita Berjón](https://github.com/MargaritaBerjon), 
[Beatriz F. León](https://github.com/Beatrizfleon), [María José](https://github.com/mjperezma),[Adhara Monzón](https://github.com/adharamonzon) y [MarinaCouso](https://github.com/MarinaCouso),


