## Integrantes del grupo

- Fiorella Miranda [cuentaGithub] (https://github.com/ellanyx)

## Descripción del disco

![Portada de álbum Vuelo](./img/solemne2-miranda-fiorella.png)

- Vuelo
- 2004
- Kudai

```txt
Tracklist 
1. Escapar
2. Sin Despertar
3. Ya nada queda
4. No quiero regresar
5. Más
6. Que aquí, que allá
7. Quiero
8. Vuelo
9. Lejos de la Ciudad
10. Dulce Y Violento
11. Escapar (Acústico)
12. Sin Despertar (Acústico)
13. Algo de Más
```

- Aspecto del álbum a desarrollar (premisa)

> La premisa de mi álbum está inspirada en la canción Sin Despertar de Kudai, la cual me genera mucha nostalgia porque mi mamá y mi hermana la escuchaban cuando yo era pequeña. A partir de la frase “sin despertar ni bajar, de esta estrella fugaz, que en su luz, vuelas tú, viajando en un cielo azul", decidí representar un cielo azul con una estrella atravesando la ciudad. Además, tomé inspiración del video original de esta canción, grabado en Parque O'Higgins, donde puede verse el cielo atrás de la banda, también se menciona el cielo nocturno en la canción, por lo que utilicé distintos tonos de azul para transmitir tanto la sensación de día como de noche.

## Conclusión del proceso

- Distancia entre premisa y resultado

> Lorem ipsum blablabla párrafo 1
>
> Lorm ipsum párrafo 2

- Cosas no conseguidas

> Lorem ipsum blablabla

- Descubrimientos al trabajar

> Lorem ipsum blablabla

## Explicación del código (3 aspectos)

### Bloque de código 1

```js
// Tu pedazo de código acá
```

### Bloque de código 2

```js
// Tu pedazo de código acá
```

### Bloque de código 3

```js
// Tu pedazo de código acá
```

### Declaración sobre el uso de IA

- IA utilizada

> Chatgpt gratis.

- Problema a resolver a través de la IA

> Hacer que la imágen png baje en diagonal desde la equina superior derecha hasta el centro a la izquierda.

- Prompts utilizados

> Quiero que la variable let star; aparezca desde la esquina superior derecha y baje en diagonal hasta el medio, cuando llegue al medio que vaya de vuelta a la esquina superior derecha en un bucle de movimiento.

> Prompt 2

> Prompt 3

- Secciones de código entregadas por la IA

```js
  // Diagonal
  posX = posX + velX * dir;
  posY = posY + velY * dir;

  // Cambia cuando llega al centro
  if (posX <= 160) {
    dir = -1;
  }
  // Cambia de posición
  if (posY >= 120) {
    dir = -1;
  }
  
  // Cuando vuelve arriba a la derecha recupera la posición inicial
  if (posX >= 320) {
    dir = 1;
  }
  // Cuando vuelve
  if (posY <= -30) {
    dir = 1;
  }
```
