# Ejercicio 7

Sea el siguiente código:

```Ada
.....
var i, z:integer;
Procedure A;
    begin
      i:= i + 1;
    end;
begin
    z:=5;
    for i:=1..5 do
    begin
        z:=z*5;
        A;
        z:=z + i;
    end;
end;
```

1. Analice en las versiones estándar de ADA y Pascal, si este código puede llegar a traer problemas. Justifique la respuesta.
2. Comente qué sucedería con las versiones de Pascal y ADA, que Ud. utilizó.

1. En ¿ADA? y Pascal estándar no se puede modificar manualmente los valores de las variables de los iteradores.
2. En ADA y Pascal no estándar se pueden modificar los valores, sin embargo el código tendría muchos problemas.
