El módulo o el operador mod divide un número por otro y devuelve el residuo. El símbolo de este operador es `%`.

```python
residuo = 5 % 2
print(residuo)

>> 1
```

El cálculo `5 / 2` es ejecutado, y se devuelve el residuo. En este caso, 2 cabe en 5 dos veces, con 1 como el residuo. Por lo tanto, el resultado es 1.

Puedes usar mod para comprobar si un número es un múltiplo de otro número. Si es así, el residuo será 0, como en este ejemplo:

```python
numero_de_prueba = 50
if numero_de_prueba  % 5 == 0:
    print("Este es un múltiplo de 5")
```
