# Ejercicio 4

Sea el siguiente programa escrito en Pascal-like

```pascal
Procedure Main;
var j, m, i: integer;
Procedure Recibe (x:integer; y:integer);
  begin
  m:= m + 1 + y;
  x:=i + x + j;
  y:=m - 1;
  write (x, y, i, j, m);
  end;
Procedure Dos;
  var m:integer;
  begin
  m:= 5;
  Recibe(i, j);
  write (i, j, m);
  end;
begin
  m:= 2;
  i:=1; j:=3;
  Dos;
  write (i, j, m);
end.
```

1. Arme el árbol de anidamiento sintáctico y el registro de activación de cada una de las unidades.

2. Decir qué imprime el programa suponiendo que para todas las variables que se pasan el pasaje de parámetros es por: (Deberá hacer la pila estática y dinámica para cada caso)
    1. Cadena estática.
       1. Referencia.
       2. Valor.
       3. Valor-Resultado.
       4. Nombre.
       5. Resultado.
    2. Cadena dinámica.
       1. Referencia.
       2. Valor.
       3. Valor-Resultado.
       4. Nombre.
       5. Resultado.
       
3. ¿Existió algún caso que no pudo realizarlo porque saltó algún tipo de error? Diga cuál y por qué.

4. ¿Dará el mismo resultado si se trata de un lenguaje que sigue la cadena dinámica? Justifique la respuesta realizando las pilas de activación.
