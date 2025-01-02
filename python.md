# Python

## Python Einführung

Python ist eine hochentwickelte Programmiersprache, die 1991 von Guido van Rossum entwickelt wurde. Sie ist bekannt für ihre einfache Erlernbarkeit und hohe Lesbarkeit des Codes, was sie ideal für Anfänger macht. Python unterstützt verschiedene Programmierparadigmen, einschließlich objektorientierter, prozeduraler und funktionaler Programmierung. 

Python verfügt über eine umfangreiche Standardbibliothek und zahlreiche Drittanbieter-Bibliotheken, was ihre Anwendung in vielen Bereichen wie Webentwicklung, Datenanalyse, künstliche Intelligenz und wissenschaftlicher Berechnung ermöglicht. 

Ein Beispiel für einen einfachen Python-Code, der „Hello, World!“ ausgibt:

    print("Hello, World!")

Die Python-Community ist sehr aktiv und bietet zahlreiche Ressourcen und Unterstützung, was das Lernen und Arbeiten mit Python erleichtert.


## Python Zeichenketten-Befehle

### 1. `len()`
Der `len()` Befehl gibt die Länge einer Zeichenkette zurück, d.h. die Anzahl der Zeichen in der Zeichenkette.

**Beispiel:**

    text = "Hallo Welt"
    länge = len(text)
    print(länge)  
>>
>> Ausgabe: 10
>>

### 2. `upper()`
Der `upper()` Befehl konvertiert alle Buchstaben einer Zeichenkette in Großbuchstaben.

**Beispiel:**

    text = "Hallo Welt"
    groß_text = text.upper()
    print(groß_text)  
>>
>> Ausgabe: HALLO WELT
>>

### 3. `replace()`
Der `replace()` Befehl ersetzt alle Vorkommen eines bestimmten Teilstrings in einer Zeichenkette durch einen anderen Teilstring.

**Beispiel:**

    text = "Hallo Welt"
    neuer_text = text.replace("Welt", "Universum")
    print(neuer_text)  
>> 
>> Ausgabe: Hallo Universum
>>