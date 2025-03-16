<!--
author:   Fachinformatiker Ausbildungsmodul
email:    ausbildung@versicherung.de
date:     16/03/2025
version:  1.0
language: de
narrator: Deutsch Female

repository: https://github.com/LiaScript/docs

logo:     https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg

comment:  Dieses Dokument stellt ein Selbstlernmodul für Fachinformatiker in Ausbildung dar.
          Der Fokus liegt auf Python-Grundlagen mit praxisnahen Beispielen aus der Krankenkassenbranche.

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css
          https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css

import:   https://raw.githubusercontent.com/liaTemplates/ABCjs/main/README.md
-->

# 📘 Python-Grundlagen für Fachinformatiker in der Krankenkassenbranche

Lerne die Grundlagen von Python und setze dein Wissen direkt in praxisnahen Aufgaben um!

## 🚀 1. Einführung in Python

Python ist eine der am häufigsten verwendeten Programmiersprachen in der Versicherungsbranche. Sie wird genutzt für:

- Automatisierte Berichte über Versicherungsfälle 📊
- Verarbeitung großer Datenmengen (z. B. Abrechnungen) 💾
- Automatisierung von Kundenanfragen 🤖

![Python Logo](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)<!-- style="width: 200px;" -->

!?[Video: Einführung in Python](https://www.youtube.com/watch?v=rfscVS0vtbw)

## 🔢 2. Erste Schritte mit Python

### 📌 Ein einfaches Python-Programm:

```python
print("Willkommen zu Python für Fachinformatiker!")
```
<script>@input</script>

### 🛠 **Aufgabe:** Ändere den Code so, dass dein Name mit ausgegeben wird.

```python
# Schreibe deine Lösung hier
print("Willkommen, [DEIN NAME]!")
```
<script>@input</script>

## 🏷️ 3. Variablen und Datentypen

Python unterstützt verschiedene Datentypen, darunter:
- **Ganzzahlen (`int`)**
- **Kommazahlen (`float`)**
- **Zeichenketten (`str`)**
- **Wahrheitswerte (`bool`)**

```python
alter = 25
versicherungskunde = "Max Mustermann"
tarif_aktiv = True

print(f"Alter: {alter}, Typ: {type(alter)}")
print(f"Kunde: {versicherungskunde}, Typ: {type(versicherungskunde)}")
print(f"Tarif aktiv: {tarif_aktiv}, Typ: {type(tarif_aktiv)}")
```
<script>@input</script>

### 🤔 **Quiz: Welcher Datentyp ist `versicherungskunde`?**

[( )] `int` - Ein Name ist keine Zahl.
[( )] `float` - Keine Kommazahl.
[(X)] `str` - Richtig! Eine Zeichenkette (String) wird für Text verwendet.
[( )] `bool` - Kein Wahrheitswert.

## 🔍 4. Praxisbeispiel: Altersprüfung für einen Tarif

In der Versicherungsbranche gelten unterschiedliche Tarife für verschiedene Altersgruppen. 
Implementiere eine Abfrage, um zu prüfen, ob eine Person einen bestimmten Tarif nutzen kann.

```python
alter = int(input("Geben Sie Ihr Alter ein: "))
if alter >= 18:
    print("Sie können diesen Tarif nutzen.")
else:
    print("Sie sind noch nicht berechtigt.")
```
<script>@input</script>

### ✏️ **Aufgabe:** Passe das Programm so an, dass nur Personen zwischen **18 und 67 Jahren** den Tarif nutzen können.

```python
# Deine Lösung hier
alter = int(input("Geben Sie Ihr Alter ein: "))
# Ergänze die Bedingung
```
<script>@input</script>

#### Musterlösung:
```python
alter = int(input("Geben Sie Ihr Alter ein: "))
if alter >= 18 and alter <= 67:
    print("Sie können diesen Tarif nutzen.")
else:
    print("Sie sind nicht berechtigt.")
```

## 💰 5. Lückencode: Monatsbeitrag berechnen

Ein Versicherungsbeitrag hängt vom Einkommen ab. Vervollständige den Code:

```python
einkommen = float(input("Geben Sie Ihr Einkommen ein: "))
if einkommen < 2000:
    beitrag = einkommen * [[0.05]]
else:
    beitrag = einkommen * [[0.08]]
print("Ihr Versicherungsbeitrag beträgt:", beitrag)
```

🔎 **Hinweis:** Nutze `0.05` für Einkommen unter 2000 € und `0.08` für Einkommen darüber.

## 🔄 6. Schleifen: Kundenkategorisierung

Kategorisiere Kunden basierend auf ihrem Alter:

```python
alter = int(input("Geben Sie Ihr Alter ein: "))

if alter <= 12:
    kategorie = "Kind"
elif alter <= 17:
    kategorie = "Jugendlicher"
elif alter <= 64:
    kategorie = "Erwachsener"
else:
    kategorie = "Senior"

print("Sie gehören zur Kategorie:", kategorie)
```
<script>@input</script>

### ✏️ **Aufgabe:** Erweitere das Programm um eine zusätzliche Kategorie für **Rentner ab 75 Jahren**.

```python
# Deine Lösung hier
```
<script>@input</script>

#### Musterlösung:
```python
alter = int(input("Geben Sie Ihr Alter ein: "))

if alter <= 12:
    kategorie = "Kind"
elif alter <= 17:
    kategorie = "Jugendlicher"
elif alter <= 64:
    kategorie = "Erwachsener"
elif alter <= 74:
    kategorie = "Senior"
else:
    kategorie = "Rentner"

print("Sie gehören zur Kategorie:", kategorie)
```

## ✅ 7. Zusammenfassung und nächste Schritte

### 📌 **Frage:** In welchen Bereichen könnte Python in der Versicherungsbranche besonders nützlich sein?

<!-- data-type="notes" -->
| Anwendungsfälle |
|:----------------|
| |

### 🧠 **Reflexion:** Nenne 3 mögliche Anwendungsfälle.

1. [[___]]
2. [[___]]
3. [[___]]

### 📚 **Weiterführende Themen:**
- Fehlerbehandlung in Python
- Arbeiten mit Datenbanken (SQL)
- Automatisierung von Berichten mit Pandas

## 🎉 Abschluss

Herzlichen Glückwunsch! 🎊 Du hast die Grundlagen von Python gelernt.

### Wissens-Check:
Was hast du gelernt? Wähle alle zutreffenden Antworten:

- [[X]] Variablen und Datentypen in Python
- [[X]] Bedingte Anweisungen (if-else)
- [[X]] Altersbasierte Kundenkategorisierung
- [[X]] Berechnung von Versicherungsbeiträgen
- [[ ]] Datenbanken mit SQL abfragen
- [[ ]] Webentwicklung mit Python

📍 **Möchtest du mit SQL als nächstem Thema fortfahren?** 

<script input="select" value="Ja" options="Ja|Nein|Vielleicht später">
"Du hast '" + @input + "' gewählt."
</script>
```
