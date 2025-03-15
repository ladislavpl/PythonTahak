[Zpět na domovskou stránku](../README.md)
# Funkce
V Pythonu můžeme vytvářet funkce. Funkce je blok kódu, který běží pouze pokud je zavolán.  To se může hodit v programech kde se v hodně částech kódu provádí ten stejný kód, akorát s jinými hodnotami.
```python
def odmocnina(n, exponent):
    return n ** 1 / exponent
print(odmocnina(27, 3))
```
*example1.py*<br><br>
V tomto příkladu jsme definovali funkci na odmocninu. Funkci definujeme pomocí def, odmocnina je název funkce a n a exponent jsou argumenty funkce, se kterými můžeme ve funkci pracovat. Return slouží k vrácení nějaké hodnoty, např. v tomto případě vracíme odmocninu nějakého čísla.<br>
Argumenty funkce slouží k tomu, aby jsme do funkce mohli vložit nějaký vstup (proměnnou, hodnotu atd.). V příkladu máme dva argumenty: n a exponent. n je číslo které chceme odmocnit, exponent je logicky exponent.<br>
V příkladovém kódu se tedy stane to, že chceme vypsat výsledek funkce odmocnina, kde do argumentu n vkládáme číslo 27 a do argumentu exponent vkládáme 3. S těmito argumenty se ve funkci může pracovat. V tomto případě provedeme odmocninu a vrátíme její výsledek který funkce print vypíše.