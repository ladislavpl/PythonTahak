[Zpět na domovskou stránku](../README.md)
# Práce s textem
Zde si uvedeme tři funkce: lower, upper a strip. Také si uvedeme formátovaní stringu pomocí F-string.
## Lower
Funkce lower slouží k tomu, aby přepsala text na malá písmena.
```python
message = "I LoVE yOu"
print(message.lower())
```
*example1.py*<br><br>
Když spustíme tento příkladový kód, vypíše se:
```
i love you
```
## Upper
Funkce upper slouží k tomu, aby přepsala text na velká písmena.
```python
message = "I LoVE yOu"
print(message.upper())
```
*example2.py*<br><br>
Když spustíme tento příkladový kód, vypíše se:
```
I LOVE YOU
```
## Strip
Funkce strip slouží k tomu, aby vám ze stringu odstranila přebytečné mezery.
```python
message = "          I love you      "
print(message.strip())
```
*example3.py*<br><br>
Když spustíme tento příkladový kód, z proměnné message se odstraní přebytečné mezery a vypíše se:
```
I love you
```
## F-String
F-string slouží k tomu, aby se dali formátovat různé části stringu. Uvedeme si to na příkladu.
```python
n = 1 + 1
print(f"Výsledek: {n}")
```
*example4.py*<br><br>
F-string vytvoříme tak, že před první uvozovku zadáme písmeno f. V F-stringu můžeme do složených závorek dávat názvy proměnných a také porovnávací operace, aritmetické operace a logické operace. U operací se vypíše její výsledek, u proměnné se vypíše její hodnota.<br>
Když by jsme spustili tento příkladový kód, vypíše se nám:
```
Výsledek: 2
```
Místo složených závorek se vypíše hodnota v proměnné uvedené v nich.