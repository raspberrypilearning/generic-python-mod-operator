De modulo of mod operator deelt het ene getal door het andere en retourneert de rest. Het symbool van deze operator is `%`.

```python
rest = 5 % 2
print(rest)

>> 1
```

De berekening `5 / 2` wordt uitgevoerd en de rest wordt terug weergegeven. In dit geval gaat 2 tweemaal in 5, waarbij 1 overblijft als de rest. Het resultaat is dus 1.

Je kunt mod gebruiken om te controleren of een getal een veelvoud is van een ander getal. Als dit het geval is, is de rest 0, zoals in dit voorbeeld:

```python
test_getal = 50
if test_getal % 5 == 0:
    print("Dit is een veelvoud van 5")
```
