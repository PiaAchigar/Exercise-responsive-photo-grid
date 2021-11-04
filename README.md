# Exercise - Responsive Photo grid - Grilla de fotos responsive ✨
### La idea era realizar una grilla de fotos responsive con la menor cantidad de lineas de código posible.
### Entonces utilicé algúnos patrónes mas avanzados:
```css
 display: grid;
 grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
 grid-auto-rows: minmax(150px, auto);
 ```
  auto-fit = Expande las columnas para que llenen toda la fila </br>
  auto-fill = Llena el espacio de columnas (sin expandirlas) y puede que queden huecos
  </br>
  ```css
  grid-auto-flow:dense;
  ```
le dice: completalo todo lo que puedas (cambia el orden)
