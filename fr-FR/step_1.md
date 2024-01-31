L'opérateur modulo, ou mod, divise un nombre par un autre et renvoie le reste. Le symbole de cet opérateur est `%`.

```python
reste = 5 % 2
print(reste)

>> 1
```

Le calcul `5 / 2` est effectué, et le reste est renvoyé. Dans ce cas, on peut mettre deux fois 2 dans 5, et il reste 1. Le résultat est donc 1.

Tu peux utiliser mod pour vérifier si un nombre est un multiple d'un autre nombre. Si c'est le cas, le reste sera 0, comme dans cet exemple :

```python
nombre_test = 50
if nombre_test % 5 == 0:
    print("Ce nombre est un multiple de 5")
```
