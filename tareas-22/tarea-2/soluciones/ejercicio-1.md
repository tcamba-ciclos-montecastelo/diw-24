1. Seleccionar todos los `<a>` y todos los `<p>`

```css
a, p {...}
```

2. Seleccionar todos los elementos `div` que descienden de un `div`

```css
div div {...}
```

3. Seleccione todos los elementos con el nombre de clase `externo` que descienden de un `div`

```css
div .externo {...}
```

4. Seleccionar todos los elementos `a` con un padre `div`

```css
div > a {...}
```

5. Seleccione todos los elementos `a` con nombre de clase `externo` y con un padre `div`

```css
div a.externo {...}
```

6. Seleccione todos los elementos `a` con nombre de clase `externo` y con un padre `div` con nombre de clase `cuerpo`

```css
div.cuerpo > a.externo {...}
```

7. Seleccione todos los elementos `button` con id `cancelButton` y nombre de clase `secundario`

```css
button#cancelbutton.secundario {...}
```

8. Seleccionar todos los hijos `div` de `#main`

```css
#main > div {...}
```

9. Seleccione todos los elementos `a` con nombres de clase `externo` y `primario`

```css
a.externo.primario {...}
```

10. Seleccionar todos los enlaces visitados

```css
a:visited {...}
```

11. Seleccionar TODOS los elementos

```css
* {...}
```

12. Selecciona todos los enlaces con `target="_blank"`

```css
a[target="_blank"] {...}
```

13. Seleccionar todos los `<p>` inmediatamente después de un `<button>`

```css
button + p {...}
```

14. Seleccionar todos los `<button>` que siguen a un hermano `.primary`

```css
.primary ~ button {...}
```

15. Selecciona todos los `<div>` que tienen un descendiente "focused"

```css
div:focus-within {...}
```

16. Selecciona todos los `<button>` que no sean `.primary`

```css
button:not(.primary) {...}
```

17. Seleccione todos los `a` "focused" con el nombre de clase `externo`

```css
a.externo:focus {...}
```

18. Selecciona todos los `<div>` que son el tercer hijo de un `<p>`

```css
p div:nth-child(3) {...}
```

20. Seleccione cualquier elemento bajo un `<nav>`, comenzando con el segundo

```css
nav :nth-child(even) {...}
```

21. Seleccione cada cuarto `<a>` bajo un `<nav>`, empezando por el segundo

```css
nav a:nth-of-type(4n+2) {...}
```

22. Seleccione todos los hijos de `<ul>` a partir del cuarto hijo

```css
ul :nth-child(n+4) {...}
```

23. Seleccione todos los `<p>` que son los últimos hijos de `.listing`

```css
.listing p:last-child {...}
```

24. Seleccione todos los descendientes del elemento con id `big-box`

```css
#big-box * {...}
```

25. Seleccione la primera línea de cada `<p>`

```css
p::first-line {...}
```

26. Seleccione cada `<img>` que sigue inmediatamente a un hermano `<a>`

```css
a + img {...}
```

27. Selecciona la primera línea de cada `<p>` que es el primer hijo de un `<article>`

```css
article > p::first-line {...}
```

28. Selecciona cada `<div>` en `.chapter` en `#main`

```css
#main .chapter div {...}
```

29. Selecciona todos los `<li>` que son descendientes del elemento con id `main`

```css
#main li {...}
```

30. Seleccione el tercer hijo de cada <ul>

```css
ul :nth-child(3) {...}
```

31. Seleccionar todos los enlaces visitados que son hijos de `<nav>`

```css
nav a:visited {...}
```

32. Selecciona todos los enlaces no visitados sobre los que se pasa el cursor pero no están enfocados

```css
a:link:hover:not(:focus) {...}
```
