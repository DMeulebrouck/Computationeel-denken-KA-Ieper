# Een eerste programma
```
#commentaar 
import math
straal = int(input("Geef de straal van de cirkel: ")
omtrek = 2 * math.pi * straal
print (omtrek)
```
## Commentaar - \#
* Wordt aangeduid met een hashtag #.
* Alles wat na de hashtag staat is commentaar, het is informatie voor de lezer.
* Dit alles wordt niet uitgevoerd.
* Commentaar mag ook na een coderegel staan.
## Module - import math
* Een module is bestaande programmacode voor specifieke problemen.
* module math : oplossingen voor wiskundeproblemen
* math.pi = het getal pi
* math.sqrt(x) = vierkantswortel van het getal tussen haakjes
## Invoer - straal = int(input("Geef de straal van de cirkel: ")
* input("...") : tekst tussen aanhalingstekens staat wordt afgedrukt op het scherm
* input("...") : de invoer van de gebruiker is altijd een tekst = string
* int(...) : tekst wordt omgezet in een geheel getal (integer)
## Uitvoer - print
* inhoud van een variabele wordt op het scherm getoond
## Datatypes
String 
* Sliert van tekens, omsloten door dubbele aanhalingstekens

Integers
* Gehele getallen (positief of negatief)

Floats
* Rationale getallen
* Resultaat van een deling is rationaal
* Wil je een geheel getal als rationaal getal gebruiken, dan moet je er .0 achter plaatsen.
* Niet altijd het precieze resultaat => afronden met round()
