# Ejercicio PHP: divisibilidad de numeros en el rango 1-100

## Solución

Cada paso se puede ir ejecutando para ir probando nuestro codigo

1. primero creamos nuestro `table` vacío
```php
<table>
</table>
```

esto es equivalente al anterior

```php
<?php
echo "<table>";
echo "</table>";
?>
```

2. ahora creamos un `tr` con sus dos respectivos `td`, usando la primera opción anterior

```php
<table>
    <tr>
        <td>
        </td>
        
        <td>
        </td>
    </tr>
</table>
```

3. en la primera columna requerimos poner los numeros del 1 al 100, por lo cual primero necesitamos poner un `for` y colocar los respectivos `{}` indicadores de bloque para encerrar la parte que que se repetirá. Este `for` nos servirá para contar de 1 a 100.

```php
<table>
    <?php
    for (){
    ?>
    <tr>
        <td>
        </td>
        
        <td>
        </td>
    </tr>
    <?php
    }
    ?>
</table>
```

4. inicializamos el `for`

```php
<table>
    <?php
    for ($x = 1; $x <= 100; $x++){ //$x++ es equivalente a $x = $x + 1 
    }
    ?>
    <tr>
        <td>
        </td>
        
        <td>
        </td>
    </tr>
    <?php
    }
    ?>
</table>
```

5. hacemos `echo` del valor de `$x` en el primer `td`, de esta manera logramos poner en la primera columnas los numeros del 1 al 100.

```php
<table>
    <?php
    for ($x = 1; $x <= 100; $x++){
    ?>
    <tr>
        <td>
        <?php
        echo $x;
        ?>
        </td>
        
        <td>
        </td>
    </tr>
    <?php
    }
    ?>
</table>
```

6. Ejecuta el codigo anterior!
