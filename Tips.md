### Tips

#### + Operator
```
<div>
  <input name="password" type="email" required autofocus>
  <label>Correo electrónico</label>
</div>
```
```
input:focus + label {
  ...
}
```
+: es el operador adyacente. Selecciona el elemento que es inmediatamente posterior al primer elemento en el árbol de DOM y que comparte el mismo padre.
En resumen, input:focus + label seleccionará un elemento label que es directamente adyacente a un input que está enfocado. 
