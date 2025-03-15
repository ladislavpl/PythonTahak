[Zpět na domovskou stránku](../README.md)
# Datové typy
```python
a = 5  # Int
pi = 3.14  # Float
name = "Ladislav" # String
isMale = True  # Boolean
array = ["banana", 3, False]  # Array
person = {  # Dictionary
    "name": "Karel",
    "surname": "Novák",
    "age": 40,
    "gender": True
}
```
*example1.py* (kód není spustitelný, můžete si na něm ale zkoušet print() a type())<br><br>
V kódu výše jsou uvedeny důležité datové typy.<br><br>
**Int:** Datový typ, který obsahuje celá čísla.<br><br>
**Float:** Datový typ, který obsahuje čísla s plovoucí desetinnou čárkou.<br><br>
**String:** Datový typ, který obsahuje text. Text se píše do uvozovek jako v příkladovém kódu.<br><br>
**Boolean:** Datový typ, který obsahuje pouze hodnoty True nebo False (Pravda/Nepravda). Počáteční písmeno hodnoty je vždy velké.<br><br>
**Array (pole):** Datový typ, který obsahuje několik hodnot pod jedním jménem. Můžeme do něj ukládat čísla, text a další hodnoty. Do array se můžou hodnoty při průběhu programu vkládat a mazat. Hodnoty se píší do hranatých závorek, oddělují se čárkou. Při zapisování jednotlivých hodnot dodržujeme pravidla pro zapisování daného datového typu. Jednotlivé hodnoty můžeme zavolat pomocí jmenoPromenne[index], kde jmenoArray je název proměnné (v příkladovém kódu je to array), a index je na jakém místě je hodnota obsažena. První hodnota je 0, druhá je 1 atd. V příkladovém kódu by jsme zavolali hodnotu "banana" pomocí array[0], protože je banana první hodnota v array.<br><br>
**Dictionary (slovník):** Datový typ, do kterého můžeme ukládat data do páru klíč:hodnota. V příkladovém kódu pokud by jsme chtěli zavolat name v slovníku person, udělali by jsme to podobně jako v poli pomocí person["name"], kde person je název proměnné (slovníku) a "name" je klíč. Za každou uloženou hodnotu musíme dát čárku, pokud chceme uložit další. Při zadávání hodnot se řídíme pravidly pro zadávání daného datového typu.<br>

### Funkce type()
Funkce type() můžeme použít k tomu aby jsme zjistili datový typ dané hodnoty/proměnné.
```python
print(type(3))
```
*example2.py*<br><br>
V tomto příkladovém kódu chceme vypsat datový typ hodnoty 3. Níže je to co nám program vypíše.
```
<class 'int'>
```
Jelikož 3 je celé číslo, datový typ této hodnoty je int.<br>
Níže naleznete jak se nazývají dané datové typy v Pythonu.<br>
```
Int - int
Float - float
String - str
Boolean - bool
Array - list
Dictionary - dict
```
Vpravo je název daného datového typu v Pythonu.
