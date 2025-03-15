[Zpět na domovskou stránku](../README.md)
# Vstup
V Pythonu můžeme použít funkci input() k tomu, aby jsme získali vstup od uživatele. Vstup se ukládá vždy do hodnoty v datovém typu string. Uvedeme si tuto funkci na příkladu.
```python
name = input()
print(f"Vaše jméno: {name}")
```
*example1.py*<br><br>
V tomto příkladu se hned na začátku programu bude požadovat vstup od uživatele. Poté ho použijeme ve výpisu. Pokud by uživatel zadal John, výstup programu by vypadal takto.
```
Vaše jméno: John
```
Tento kód můžeme ještě vylepšit tím, že se uživateli když program bude vyžadovat vstup nezobrazí pouze prázdno, ale zobrazí se daný text za který se bude zadávat vstup. Tento text není součástí vstupu, je pouze pro lepší porozumění uživatele tomu co po něm program chce.
```python
name = input("Zadejte vaše jméno: ")
print(f"Vaše jméno: {name}")
```
*example2.py*<br><br>
Když program bude vyžadovat vstup, bude to vypadat takto:
```
Zadejte vaše jméno: 
```