# Markdown in Visual Studio Code
Markdown ist eine vereinfachte Auszeichnungssprache, die von John Gruber und Aaron Swartz entworfen und im Dezember 2004 mit Version 1.0.1 spezifiziert wurde. Ein Ziel von Markdown ist eine leicht lesbare Ausgangsform bereits vor der Konvertierung. Als Auszeichnungselemente wurden daher vor allem Auszeichnungsarten verwendet, die in Plain text und E-Mails üblich sind. Auch andere Auszeichnungssprachen mit ähnlichen Zielen zur Lesbarkeit – wie reStructuredText oder Textile – hatten Einfluss auf die Syntax. Der MIME-Type lautet text/markdown.

---

## Mathematische Formeln
Formeln werden in $$-Zeichen eingefasst.

---
### Beispiele
1. $a²+b²=c²$

2. $\sqrt{2x+5}$

3. $\frac{3x+5-7}{2x²-1}$

4. $\lim\limits_{n \rightarrow \infty}{a_n}$

5. $\sum_{k=1}^n \limits k=\frac{n(n+1)}{(2)}$
---

## Darstellen von Code
Code wird in Markdown in je 4 Backticks eingefasst.(````)

---

### Beispiele
#### Java


````Java
for(int i=0; i<=10; i++){
    System.out.print("Hallo Welt"+i)
}
````

````Python
# wurzel.py

a = float(input("Zu berechnende Quadratwurzel: "))

x = float(input("Startwert x1: "))

# float bedeutet, dass mit Kommazahlen gerechnet werden soll!  

print ("Iteration  Näherungswert")

print ("_________________________")   

for i in range(1,6):

  x = 0.5*(x+a/x)

  print ('   ',i,'    ',x)
````

---

## Einfach Formatieren

1. Dieses Wort ist **Fett**
2. Dieses Wort ist _Kursiv_

---

> ## Blockquotes
> ### Mithilfe von ">" kann mann Merkkästen erstellen

---

## Tabellen
|Name|Geschlecht|Noch zu Zahlen|
|:-     |:-: |-:|
|Max    |M| 3,75|
|Sarah  |W| 10000000000000000000000 Bitcoin $* 2^2*10000000^7$|

---

## Listen
1. Punkt 1
2. Punkt 2
    - halber Punkt 1
    - halber Punkt 2

- voller Punkt 1
- voller Punkt 2
    - halber Punkt 3

---

## Links
1. Hyperlink mit eigenem text
[Website Sebastian](https://www.google.com)

2. Hyperlink direkt eingeben
https://google.com

3. [Link auf Datei](./test.md)
Es kann auch eine Variablefür einen Link erstellen

4. Link auf eine Überschrift erreichet man, indem man die Überschrift klein schreibt und Leerstellen mit "-"
verbindet. Hier ein Link auf [Tabellen](tabellen)

---