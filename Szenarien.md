#Job1: 

Die Kundenfirma Protomax sucht spezifische **Manufacturing Services** für 5 Komponenten, die in den neuen Produkt-Prototypen NovoXP der Firma eingebaut werden sollen.

OP 1. Ein Bauteil mit den Dimensionen 180x180x200 mm, das aus rotem ABS Material bestehen soll:

    - Benötigt: 3D-Drucker (Fused Filament Fabrication)
    - Dimensionen: 180x180x200
    - Material: ABS rot
    - H_ij= {2, 5}
    
OP 2. Eine Stahlwelle mit den Dimensionen 300x10 mm (Durchmesser):

    - Benötigt: Drehmaschine
    - Dimensionen: 300*10D
    - Material: Stahl
    - H_ij= {14,15}
 
OP 3: Ein Bauteil mit den Dimensionen 12x18x25mm, das aus flexiblem Material zur Schwingungsdämpfung bestehen soll:

    - Benötigt: Guss
    - Dimensionen: 12x18x25
    - Material: Eigenschaft: flexibel, Schwingungsdämpfend
    - H_ij= {19,20,21}
  
OP 4: Eine zweischichtige elektronische Leiterplatte mit den Dimensionen 100x50x3mm zur Bestückung mit einer Schaltung:

    -Benötigt: Leiterplattenerstellung
    -Dimensionen: 100x50, zweischichtig
    -Material: 
    -H_ij= {22,23,24}
    
OP 5. Bestückung der in OP 4 erwähnten Leiterplatte: 

    - Benötigt: Leiterplattenbestückung
    - Dimensionen: 100x50, zweischichtig
    - Material: 
    - H_ij= {25,26,27}
    
OP 6. Ein Bauteil mit den Dimensionen 190x190x320mm, das aus gelbem Epoxidharz bestehen soll:

    - Benötigt: Guss
    - Dimensionen: 190x190x320
    - Material: Epoxidharz
    - H_ij= {19,20,21}
    
**Damit:**

    6 [2] {2 3} {5 5} [2] {14 4} {15 5} [3] {19 5} {20 6} {21 8} [3] {22 4} {23 3} {24 6} [3] {25 5} {26 4} {27 6} [3] {19 5} {20 6} {21 8} [(0 45 1)]
    6 2 2 3 5 5 2 14 4 15 5 3 19 5 20 6 21 8 3 22 4 23 3 24 6 3 25 5 26 4 27 6 3 19 5 20 6 21 8 0 45 1

**Job2:** (Permutation von Job1 (Vertauschung der Reihenfolge))

    6 3 19 5 20 6 21 8 3 25 5 26 4 27 6 3 19 5 20 6 21 8 2 14 4 15 5 3 22 4 23 3 24 6 2 2 3 5 5 0 35 2
    
**Job3:** (Permutation von Job1 (Vertauschung der Reihenfolge))

    6 2 14 4 15 5 3 25 5 26 4 27 6 3 19 5 20 6 21 8 3 19 5 20 6 21 8 2 2 3 5 5 3 22 4 23 3 24 6 0 40 3
    
**Job4:** (Permutation von Job1 (Vertauschung der Reihenfolge))

    6 2 14 4 15 5 3 19 5 20 6 21 8 2 2 3 5 5 3 19 5 20 6 21 8 3 25 5 26 4 27 6 3 22 4 23 3 24 6 0 50 2
    
**Job5:** (Permutation von Job1 (Vertauschung der Reihenfolge))

    6 3 19 5 20 6 21 8 2 2 3 5 5 3 25 5 26 4 27 6 2 14 4 15 5 3 19 5 20 6 21 8 3 22 4 23 3 24 6 0 45 3
 
#Job 6:

Ein Student nutzt einen Service für sein Abschlussprojekt, der folgende Operationen anbieten soll:

  OP1 Erstellung einer Leiterplatte,     H_ij= {12,13,22,23,24}
  
  OP2. Bestückung der Leiterplatte mit SMD-Bauteilen,     H_ij= {25,26,27}
  
  OP3: Druck des ersten Teiles des Gehäuses in grau, H_ij= {0,5}
  
  OP4: Druck des zweiten Teiles des Gehäuses in weiß, H_ij= {1,6}
  
  OP5: Druck der Abdeckung im Holz–Stil, H_ij= {3,4}
  
  OP6: Spezialanfertigung eines stabilen Metallrahmens im Sinterverfahren, H_ij= {7,8,9}
  
  OP7: Ein gedrehtes Stahlteil, H_ij= {14,15}
  
**Damit:**

    7 5 12 3 13 4 22 6 23 4 24 5 3 25 6 26 5 27 4 2 0 3 5 4 2 1 2 6 3 2 3 6 4 7 3 7 7 8 8 9 6 2 14 5 15 4 0 50 1

**Job7:** (Permutation von Job6 (Vertauschung der Reihenfolge))

    7 2 1 2 6 3 5 12 3 13 4 22 6 23 4 24 5 3 25 6 26 5 27 4 2 0 3 5 4 2 3 6 4 7 3 7 7 8 8 9 6 2 14 5 15 4 0 55 2

**Job8:** (Permutation von Job6 (Vertauschung der Reihenfolge))

    7 2 14 5 15 4 2 3 6 4 7 2 1 2 6 3 2 0 3 5 4 5 12 3 13 4 22 6 23 4 24 5 3 25 6 26 5 27 4 3 7 7 8 8 9 6 0 55 1

**Job9:** (Permutation von Job6 (Vertauschung der Reihenfolge))

    7 2 14 5 15 4 2 3 6 4 7 2 1 2 6 3 3 25 6 26 5 27 4 5 12 3 13 4 22 6 23 4 24 5 2 0 3 5 4 3 7 7 8 8 9 6 0 50 3

**Job10:** (Permutation von Job6 (Vertauschung der Reihenfolge))

    7 2 0 3 5 4 3 25 6 26 5 27 4 5 12 3 13 4 22 6 23 4 24 5 2 1 2 6 3 2 3 6 4 7 3 7 7 8 8 9 6 2 14 5 15 4 0 50 1


#Job 11:
Ein visionäres Startup möchte in Südeuropa mit innovativen Bautechniken experimentieren:

  OP1: Beton-Druck einer optimierten Konstruktion;  H_ij={10,11}
  
  OP2: Beton-Druck einer paraboloiden Konstruktion;  H_ij={10,11}
  
  OP3: Beton-Druck einer hyperbolischen Konstruktion;  H_ij={10,11}
  
  OP4: Sonderanfertigung einer Vorrichtung aus Metall;  H_ij= {7,8,9}
  
  OP5: Boden-Sample aus Epoxidharz mit Isolierenden Eigenschaften;  H_ij={19,20,21}
  
**Damit:**

    5 2 10 8 11 7 2 10 9 11 8 2 10 10 11 9 3 7 5 8 4 9 8 3 19 5 20 6 21 8 0 30 1

**Job12:** (Permutation von Job11 (Vertauschung der Reihenfolge))

    5 3 19 5 20 6 21 8 2 10 10 11 9 2 10 8 11 7 2 10 9 11 8 3 7 5 8 4 9 8 0 25 2

**Job13:** (Permutation von Job11 (Vertauschung der Reihenfolge))

    5 3 19 5 20 6 21 8 3 7 5 8 4 9 8 2 10 10 11 9 2 10 8 11 7 2 10 9 11 8 0 25 3

**Job14:** (Permutation von Job11 (Vertauschung der Reihenfolge))

    5 2 10 10 11 9 2 10 8 11 7 2 10 9 11 8 3 7 5 8 4 9 8 3 19 5 20 6 21 8 0 30 4

**Job15:** (Permutation von Job11 (Vertauschung der Reihenfolge))

    5 3 7 5 8 4 9 8 2 10 8 11 7 2 10 9 11 8 2 10 10 11 9 3 19 5 20 6 21 8 0 35 4


##FJSS:

    15 28
    6 2 2 3 5 5 2 14 4 15 5 3 19 5 20 6 21 8 3 22 4 23 3 24 6 3 25 5 26 4 27 6 3 19 5 20 6 21 8 0 45 1
    6 3 19 5 20 6 21 8 3 25 5 26 4 27 6 3 19 5 20 6 21 8 2 14 4 15 5 3 22 4 23 3 24 6 2 2 3 5 5 0 35 2
    6 2 14 4 15 5 3 25 5 26 4 27 6 3 19 5 20 6 21 8 3 19 5 20 6 21 8 2 2 3 5 5 3 22 4 23 3 24 6 0 40 3
    6 2 14 4 15 5 3 19 5 20 6 21 8 2 2 3 5 5 3 19 5 20 6 21 8 3 25 5 26 4 27 6 3 22 4 23 3 24 6 0 50 2
    6 3 19 5 20 6 21 8 2 2 3 5 5 3 25 5 26 4 27 6 2 14 4 15 5 3 19 5 20 6 21 8 3 22 4 23 3 24 6 0 45 3
    7 5 12 3 13 4 22 6 23 4 24 5 3 25 6 26 5 27 4 2 0 3 5 4 2 1 2 6 3 2 3 6 4 7 3 7 7 8 8 9 6 2 14 5 15 4 0 50 1
    7 2 1 2 6 3 5 12 3 13 4 22 6 23 4 24 5 3 25 6 26 5 27 4 2 0 3 5 4 2 3 6 4 7 3 7 7 8 8 9 6 2 14 5 15 4 0 55 2
    7 2 14 5 15 4 2 3 6 4 7 2 1 2 6 3 2 0 3 5 4 5 12 3 13 4 22 6 23 4 24 5 3 25 6 26 5 27 4 3 7 7 8 8 9 6 0 55 1
    7 2 14 5 15 4 2 3 6 4 7 2 1 2 6 3 3 25 6 26 5 27 4 5 12 3 13 4 22 6 23 4 24 5 2 0 3 5 4 3 7 7 8 8 9 6 0 50 3
    7 2 0 3 5 4 3 25 6 26 5 27 4 5 12 3 13 4 22 6 23 4 24 5 2 1 2 6 3 2 3 6 4 7 3 7 7 8 8 9 6 2 14 5 15 4 0 50 1
    5 2 10 8 11 7 2 10 9 11 8 2 10 10 11 9 3 7 5 8 4 9 8 3 19 5 20 6 21 8 0 30 1
    5 3 19 5 20 6 21 8 2 10 10 11 9 2 10 8 11 7 2 10 9 11 8 3 7 5 8 4 9 8 0 25 2
    5 3 19 5 20 6 21 8 3 7 5 8 4 9 8 2 10 10 11 9 2 10 8 11 7 2 10 9 11 8 0 25 3
    5 2 10 10 11 9 2 10 8 11 7 2 10 9 11 8 3 7 5 8 4 9 8 3 19 5 20 6 21 8 0 30 4
    5 3 7 5 8 4 9 8 2 10 8 11 7 2 10 9 11 8 2 10 10 11 9 3 19 5 20 6 21 8 0 35 4

 
