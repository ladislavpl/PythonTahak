[Zpět na domovskou stránku](../README.md)
# Cykly
V Pythonu máme různé cykly.
## While
Cyklus while dělá to, že se bude daný kód opakovat, dokud je podmínka platná.
```python
while x <= y:
    print("Apple")
```
*example1.py* (kód není spustitelný, musíte přidat proměnnou x a y s nějakým číslem aby kód fungoval)<br><br>
V tomto příkladu se bude vypisovat slovo Apple do té doby, dokud bude x menší nebo rovno y. Samozřejmě musíme použít odsazení.<br>
Pomocí while můžeme také opakovat nějaký kód do nekonečna. To můžeme udělat pomocí while True:
```python
while True:
    print("Apple")
```
*example2.py*<br><br>
V tomto příkladu se slovo Apple bude vypisovat do nekonečna (dokud program ručně neukončíte)
## For
Cyklus for se používá ve dvou případech.<br>
```python
for i in range(0, 3, 1):
    print("Raspberry")
```
*example3.py*<br><br>
V tomto příkladu je cyklus for použit k tomu, aby se kód opakoval daný počet kol. Do range jako první vložíme na jakém čísle chceme začínat (v tomto případě 0, je to také výchozí hodnota), jako druhé na jakém čísle chceme končit (v tomto případě 3, tuto hodnotu vždy musíme zadat), a o kolik chceme postupovat (v tomto případě 1, je to výchozí hodnota). V praxi se nám slovo Raspberry vypíše 3x.<br>
Tento cyklus můžeme zjednodušit takto:
```python
for i in range(3):
    print("Raspberry")
```
*example4.py*<br><br>
Hodnota na jakém čísle chceme začínat a o kolik chceme postupovat je nepovinná. Pokud jí nezadáte, použíjí se výchozí hodnoty.<br><br>
```python
fruits = ["Raspberry", "Orange", "Apple"]
for x in fruits:
    print(x)
```
*example5.py*<br><br>
V tomto příkladě je použito druhé využití cyklu for. Cyklus for takto vypíše postupně každou hodnotu v poli fruits. x v tomto cyklu je v prvním kole první hodnota v poli fruits, v druhém kole druhá hodnota..., a tento cyklus se opakuje tak dlouho, dokud se nedojde až k poslední hodnotě. Použití vychází i z překladu do češtiny pro x ve fruits. Za in zadáváme název pole, za for zadáváme jméno proměnné, která bude obsahovat danou hodnotu z pole.
## Prohlášení break
S prohlášením break můžeme zastavit opakování cyklu i před tím, než je cyklus dokončen.
```python
fruits = ["Raspberry", "Orange", "Apple"]
for x in fruits:
    if x == "Orange":
        break
    print(x)
```
*example6.py*<br><br>
V tomto příkladu se stane to, že se budou vypisovat hodnoty z pole fruits a pokud se dojde k hodnotě Orange, vypisování se zastaví.
## Prohlášení continue
S prohlášením continue můžeme přeskočit kolo cyklu a přesunout se na další.
```python
fruits = ["Raspberry", "Orange", "Apple"]
for x in fruits:
    if x == "Orange":
        continue
    print(x)
```
*example7.py*<br><br>
V tomto příkladu se stane to, že se budou vypisovat hodnoty z pole fruits a pokud se dojde k hodnotě Orange, kolo se přeskočí a Orange se nevypíše.