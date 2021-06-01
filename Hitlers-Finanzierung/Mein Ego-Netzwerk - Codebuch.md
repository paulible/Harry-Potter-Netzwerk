CODEBUCH,
"Im Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden.",
,
Wert,Kommentar
edgelist,Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).
from,"definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort"
to ,"definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. "
weight,"Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen. Skala: 1 = indirekte Unterstützung, 2= passive Wegebnung/Hilfe, 3 = aktive Wegebnung/Hilfe"
time,"definiert einen Zeitraum, in dem die Beziehung zwischen zwei Knoten stattgefunden hat oder beobachtet wurde."
nodelist,Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.
id,"eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  "
name,Name oder Bezeichnung des Knotens. 
sex,"dichotome Ausprägung: 1 = male, 2 = female"
work,"definiert, aus welcher Branche die Knoten kommen; 1 = Politik, 2 = Wirtschaft"
type,"definiert, um welche Art von Knoten es sich handelt; 1 = Person, 2 = Organisation"
money,"definiert die Geldbeträge 1 = 0-10 Tsd., 2 = 10-20 Tsd., 3 = 20-50 Tsd., 4 = 50-100 Tsd., 5 = 100 Tsd. <"
moneytype,"definiert die Art des Geldflusses; 1 = Darlehen, 2 = Kredit, 3 = Spenden"
timeframe,"definiert die Häufigkeit der Spenden; 1 = einmalig, 2 = regelmäßig"
country,"definiert die Herkunft der Geldgeber; 1 = Schweiz, 2 = Amerika, 3 = Deutschland, 4 = Österreich, 5 = England, 6 = Russland, 7 = sonstige "