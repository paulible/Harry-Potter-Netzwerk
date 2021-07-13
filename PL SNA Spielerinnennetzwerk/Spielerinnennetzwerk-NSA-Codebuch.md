# Codebuch Spielerinnennetzwerk #
Codebuch Stand 14. Juli 2021,  
erstellt von Paulina Blech

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# EDGE-Attribute

**relation**   
Definiert die Art der Beziehung  

1 = Heimatland/Nationalität,    
2 = Verrein in welchem die Spielerin gespielt hat.

# NODE-Attribute  
  
**id**  
Eindeutige Identifikation jedes einzelnen Knotens, der erfasst wird. In diesem Fall  Spielerinnen, Vereine und Länder/Nationalitäten.

**name**  
Name oder Bezeichnung des Knotens, wie sie nachher im visualisierten Netzwerk angezeigt werden.

**type**    
Definiert, um welche Art von Knoten es sich handelt.  

0 = Person,  
1 = Organisation wie Verein und Land/Nationalität.
  
**birth**    
Definiert das Jahr, in welchem die Spielerin geboren ist, (numerisch in Jahreszahlen).   

**age**   
Definiert, das Alter der Spielerinnen  

1 = unter 20 und 20 Jahre alt,   
2 = 21-23 Jahre alt,  
3 = 24-26 Jahre alt,  
4 = über 27 Jahre alt.

**position**    
Definiert die Position der Spielerin auf dem Feld  

1 = Mittelblock,  
2 = Zuspiel,  
3 = Außenangriff,  
4 = Diagonal,  
5 = Libera. 
  
**country**  
Definiert die Herkunft der Spielerin.  

1 = Niederlande,       
2 = Bulgarien,    
3 = Deutschland,  
4 = Belgien,   
5 = Polen,   
6 = USA,   
7 = Spanien,   
8 = Finnland.


##
