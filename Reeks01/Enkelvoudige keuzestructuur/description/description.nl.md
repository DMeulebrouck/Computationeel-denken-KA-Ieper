# Een booleaanse expressie

Expressie = combinatie van waarden, constanten, variabelen, operatoren en functies die geïnterpreteerd of geëvalueerd wordt 
volgens bepaalde regels en vervolgens uitgerekend om uiteindelijk 1 waarden op te leveren.

Een booleaanse expressie geeft als resultaat waar (True) of onwaar (False)<br>
True en False zijn waarden van het type 'bool'
	
Bewerkingen of booleaanse expressies zijn super handig wanneer we gaan programmeren, ze laten toe om de te volgen bewerkingen te laten afhangen 
van het al dan niet waar zijn van een bewering : ALS … DAN …

# Het if-statement  (als … dan …)
Dit statement beschrijft welke taken er moeten uitgevoerd worden wanneer een bepaalde booleaanse expressie True is.<br>
Voorbeeld:
```
    ALS <<je portefeuille is leeg>> DAN <<haal geld af van je spaarrekening>>
    
    ALS <<de vuilzak is vol>> DAN
 	<<haal volle vuilzak uit vuilnisemmer>>
 	<<zet volle vuilzak buiten>>
	<<neem een lege vuilzak>>
	<<steek lege vuilzak in vuilnisemmer>>
```
door het inspringen weet Python dat de 4 volgende opdrachten als een blok moeten worden uitgevoerd.<br>

ALS => if <br>
DAN => : 
	
	If <<booleaanse expressie >> : 
	     <<taak 1>>
	     <<taak 2>> 
	     <<taak 3>>
	
	getal = int(input("Geef een geheel getal op : "))
	if getal > 100 :
	   print ("amai,")
	   print ("dat is echt wel een groot getal")
	   print ("allez, ik bedoel het getal is groter dan 100")
	print ("het programma is afgelopen")

# Relationele operatoren
 
| Operator  | Uitleg       | 
|:---:|:---|
| <  | kleiner dan           | 
| <= | kleiner dan of gelijk aan |
| >  | groter dan      |
| >= | groter dan of gelijk aan      |
| == | gelijk aan|
| != | verschilt van |

