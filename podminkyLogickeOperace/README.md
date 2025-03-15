[Zpět na domovskou stránku](../README.md)
# Podmínky a logické operace
V Pythonu existují různé podmínky a logické operace.
```python
if 5 == 5: # Zjišťujeme jestli se 5 rovná 5
    print("Hello World")
elif 5 != 5: # Pokud se 5 nerovná 5, zjistíme jestli se 5 nerovná 5
    print("Orange")
else: # Pokud ani jedna z podmínek není platná
    print("Apple")
```
*example1.py*<br><br>
V kódu výše je použita podmínka if, elif a else.<br><br>
If slouží k tomu, aby jsme zjistili pomocí porovnávání a logických operací jestli je nějaké tvrzení pravivé. Pokad ano, provede se daná operace. Zadáváme if podmínka: a příkazy zadáváme pod dvojtečku s odsazením. Python totiž závisí na odsazení.<br><br>
Elif slouží k tomu, když se podmínka nad ním nestane platnou, tak se přejde na elif a zkontroluje se, jestli podmínka na elif je platná. Pokud ano, provede se kód za elif. Takto můžete pod sebou použít více podmínek elif a testovat např. 3x jestli je podmínka platná. <br><br>
Else slouží k tomu, pokud ani jedna podmínka uvedená na if (případně elif) není platná, provede se kód za else.<br><br>
Níže jsou uvedeny porovnávací operace:
```
== (je rovno)
!= (není rovno)
> (větší než)
< (menší než)
>= (větší nebo rovno)
<= (menší nebo rovno)
```
V Pythonu máme také logické operace.
### And
```python
if 5 == 5 and 5 < 6:
    print("Watermelon")
```
*example2.py*<br><br>
Pokud použijeme operaci and, podmínka bude platná pouze v tu chvíli, pokud obě či více podmínek jsou platných.<br>
V příkladu se vypíše slovo Watermelon pouze, pokud 5 je rovno 5 a 5 je menší než 6. 
### Or
```python
if 5 == 5 or 6 == 4:
    print("Watermelon")
```
*example3.py*<br><br>
Pokud použijeme operaci or, podmínka bude platná pouze v tu chvíli, pokud jedna z podmínek bude platná.<br>
V příkladu se vypíše slovo Watermelon pouze, pokud 5 je rovno 5 nebo 6 je rovno 4.