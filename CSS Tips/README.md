# CSS Tips

Lista de codigos css que me pueden servir.


### Blanquear img svg

Actualmente no se puede colorear un svg que no es llamado vía '<svg>' por ende la única forma de colorearlo es vía filtros css.

El filtro Brightness o Brillo, al manejarse en porcentajes nos permite poder agregar brillo a nuestra imagen, es decir, en 10, tendremos nuestro logo en white, y en 0 nuestro logo en negro.

```
img.class {
    -webkit-filter: brightness(10);
    filter: brightness(10);
}
```