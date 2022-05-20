# Datensatz Transfers des VfB Kaders 2022 #
Codebuch 20.05.2022

erstellt von Stefanie Lauterbach (sl144)


## Inhalt
- Edgelist.csv (Edgelist)
- Nodelist.csv (Nodelist)
- codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Das Netzwerk wurde aus folgenden Daten erstellt:

https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79



Es wurden die Transfers zum VFB für das jetzige Kader analysiert:

-Von welchen Vereinen kommen die Spieler?
-Welche Nationalität haben Sie? 
-Was wurde für Sie bezahlt? 



**Umgang mit fehlenden Werten**

Fehlende Werte werden nicht erfasst.



# EDGE-Attribute

**from**

Von welchem Verein kommt der Spieler/ID des Spielers


**to**

ID des Spielers (Rückennummer)/Nationalität des Spielers


**weight**  

Transfersumme in 100.000 Euro Schritten, gerundet falls abweichend.


**season**

Transferfenster (nur die erste Jahreszahl)



# NODE-Attribute  
  
**id** 

Rückennummer oder Vereinsname


**name**

Spieler oder Vereinsname


**country** 

Land


**type**

type 1 = Spieler, 2 = Verein

##
