# Tu primera aplicación Angular

## 4. Crear Componente

Hasta ahora hemos aplicado muchos conceptos a nuestra aplicación, ahora es tiempo de profundizar un poco más. Vamos a crear nuestro propio componente 📦.

En Stackblitz:

1. Click derecho en la carpeta `app`
2. Selecciona `Angular Generator`
3. Y luego click a `component`. Nombra el componente como tu quieras, por ejemplo: `my-component`

![stackblitz](gen.png)

Un componente generalmente está compuesto por:

- 🔧 **Componentes:** `my-component.component.ts`
- 🎨 **Estilos:** `my-component.component.css`
- 📱 **Template o HTML:** `my-component.component.html`
- 📋 **Pruebas:** `my-component.component.specs.ts`

>  Un componente es una manera de tener una aplicación más mantenible en el tiempo(i.e. esto es muy útil cuando tu aplicación crece).

El **template** contiene algo como esto por defecto:

```html
<p>my-component works!</p>
```

1. Ahora, Abrimos nuestro componente: `my-component.component.ts`
2. Fijate en la etiqueta selector, debería ser algo como esto: `app-my-component`

> El `selector` es ña etiqueta que puedes usar para mostrar tu compnente dentro de otra vista o template.

Ahora que sabemos la etiqueta de nuestro componente, podemos usarla dentro de nuestro app component (**El componente original en el que estabamos trabajando**).

1. Abre `app.component.html` Y agrega esto al final: `<app-my-component></app-my-component>`
2. Mira tu aplicación en el navegador! 💕
3. Si ves **my-component** rederizado, Entonces ¡lo hiciste! 💪

## Tu Misión! ⏳

Mueve la lógica, el template, y los estilos del componente **app** a **my-component**.

### Pistas 👇

1. La aplicación debería seguir funcionando.
2. Mueve todo, excepto la etiqueta`<app-my-component></app-my-component>`, es necesaria para renderizar **my-component**.

## Lo hiciste! 👏

Haz creado una aplicación súper mantenible! 👏👏👏

Eso es todo!

