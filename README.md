# Tu primera aplicación Angular

## 1. String interpolation

Tu aplicación debe estar corriendo y funcionando 👌. Ahora es tiempo de empezar a hacer cambios:

Una característica genial de angular se llama **string interpolation**. que permite enlazar tus variables a tu template(HTML o Vista). Empecemos:

1. Abre el archivo `app.component.html` y reemplaza **Todo su contenido** con: `<h1>This is cool! 😃</h1>`
2. Guarda el archivo y mira los cambios. Debería funcionar inmediatamente!
3. Ahora, abre `app.component.ts` y encuentra la variable `name` 
4. Reemplaza su contenido con: `'TuNombre'`
5. Finalmente vuelve a `app.component.html` y agrega esto:

```html
<h1>This is cool! 😃</h1>
<h2>My name is {{ name }} </h2>
```

8. Guarda el archivo y mira los resultados automáticamente en el navegador 👌👌👌

Asegurate que tu nombre este ahí! 💕 Intenta con mas variables!

![results](result.png)

## Lo hiciste, Ahora pasa a la [rama #2](https://github.com/jdjuan/your-first-angular-application/tree/2#your-first-angular-application)
