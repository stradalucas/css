### Tips

#### + Operator
```
<div>
  <input name="password" type="email" required autofocus>
  <label>Correo electrónico</label>
</div>
```
```
input:focus + label,
input:not(:placeholder-shown) + label
{
  ...
}
```
input:focus + label, seleccionará un elemento label que es directamente adyacente a un input que está enfocado. 
input:not(:placeholder-shown) + label, se aplicará si el placeholder no se está mostrando, es decir, el input no está vacío.
