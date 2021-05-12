# Die Transfers der deutschen Fußball-Bundesliga #
Codebuch Stand 2021-05
erstellt von Swaran Sandhu (sandhu@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# NODE-Attribute  
  
**id**  
Eindeutige Bezeichnung der Knoten. In der Regel bis zu vier Zeichen.

**name**
Voller Name der Vereine bzw. der Ligen.

**type**
Art des Knoten


1 = Verein

2 = Ligen (unterklassige deutsche bzw. ausländische Ligen)

**level**
Das Niveau der Liga anhand der Fünfjahreswertung der UEFA und eigener Kategorisierung


1 = "Big Five" in Europa

2 = Platz 6 bis 22 inkl. der 1. Ligen in Brasilien, USA und China (als gefragte außereuropäische Ligen)

3 = Rest der Welt

**region**

Regionale Aufteilung

# EDGE-Attribute

**playername**

Name des transferierten Spielers

**transfersumme**

Transfersumme

**weight**

Kategorisierte Einteilung der Transfersumme


1 = ablösefrei

2 = bis 100.000€

3 = 100.000€ - 500.000€

4 = 500.000€ - 1.000.000€

5 = 1.000.000€ - 5.000.000€

6 = 5.000.000€ - 10.000.000€

7 = über 10.000.000€


**transfertype**

Kategorisierung des Transfers


1 = Fixer Transfer

2 = Leihgeschäft


**year**

Jahr des Transfers


**transferfenster**

Zeitraum des Transfers

1 = Sommertransferfenster

2 = Wintertransferfenster

###
