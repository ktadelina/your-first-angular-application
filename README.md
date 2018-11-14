# Tu primera aplicación Angular

## 2. Event binding

Event binding nos permite agregar eventos a elementos o componentes e.g. `Click`, `Keyup`, muchos otros ✌️

Empecemos nuestro primer evento:

1. Abre `app.component.html` y crea un botón: `<button>Click me 💪</button>`.
2. Verifica si se muestra 👌
3. abre tu archivo `app.component.ts` y crea una nueva variable llamada **count** y inicializa la misma en **0**: `count = 0;`
4. ¡Bien!, Aquí está tu primera misión: Usa **String Interpolation** para mostrar en la vista nuestra nueva variable. 🤡  Que empiece el juego... 🤡 Vamos, hazlo.
5. ⏰⏰⏰
6. **Estas list@?** Cool! 💪
7. Es tiempo de agregar nuestro evento,cambia el botón acorde a esto:

```html
<button (click)="count = count + 1" >Add 1</button>
```

8. Mira el navegador y prueba!
9. Funcionó? Cooool! 🎉🎉🎉

![result](result.png)

## Lo hiciste, ahora la [rama #3](https://github.com/jdjuan/your-first-angular-application/tree/3#your-first-angular-application)
