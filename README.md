# Use Case Scenario

1. Das Rahmenszenario - das den konkreten Profactor use case als EINE Ausprägung unterstützt.

  1.  Die Kundenfirma **Protomax** sucht spezifische Manufacturing Services für 5 Komponenten, die in den neuen Produkt-Prototypen **NovoXP** der Firma eingebaut werden sollen.
  2.  Die 5 **Komponenten** des NovoXP Prototypen sind:
    1.  ein Bauteil mit den Dimensionen 180x180x200 mm, das aus rotem ABS Material bestehen soll
    2.  eine Welle mit den Dimensionen 300x10 mm (Durchmesser), aus Stahl
    3.  ein Bauteil mit den Dimensionen 12x18x25mm, das aus flexiblem Material zur Schwingungsdämpfung bestehen soll.
    4.  eine zwei-schichtige elektronische Leiterplatte mit den Dimensionen 100x50x3mm zur Bestückung mit einer Schaltung
    5.  Ein Bauteil mit den Dimensionen 190x190x320mm, das aus gelbem Epoxydharz bestehen soll.
  3.  Es gibt eine **Manufacturing Services Platform NIMBLE.AT**, auf der Hersteller ihre Dienstleistungen anbieten können.
  4.  Es gibt **8 Manufacturing firms**, die insgesamt 10 Leistungen teilweise überlappend, anbieten können: Tri-Druck, LeiterPro, Filamenti, PlasticniNozzle, Betonista, EPX Ltd., Lathes Ltd., All-In-Pro GmbH.
  5.  Die **10 Leistungen** sind:
    1.  ABS und PLA 3D Druck (verschiedene Drucker mit unterschiedlichen X,Y,Z Maxima, und unterschiedlichen Nozzle-Größen, sowie Schichthöhen.
    2.  Metall-3D-Drucker
    3.  Holz-3D-Drucker
    4.  Beton-Formen Drucker für die Bauindustrie
    5.  Einschichtiger Leiterplattendruck in 3D (additiv)
    6.  Drehteile bis 1000mm und 300mm Durchmesser (Verschiedene Bearbeitungsmaschinen)
    7.  3D Filament-Herstellung (ABS, PLA, Flexi, etc) --> Anmerkung: das kann im Szenario dazu benützt werden eine Supply-Chain zu illustrieren: Filament-Hersteller > 3-Druckfarm > Platform > 3D-Service-Kunde
    8.  Epoxidharz-Guß (verschiedene Maschinen mit unterschiedlichen X,Y,Z Maxima).
    9.  mehrschichtige Leiterplattenproduktion klassisch
    10.  Bestückungsautomaten für Leiterplatten
  6.  Für jede Leistung gibt es mindestens **2 Alternativen, die sich in Preis, Zeit, Qualität und/oder Dimensionen** unterscheiden, d.h. wir haben es mit **mindestens 20 Maschinen** zu tun.

2. Das Profactor / SRFG Optimierungsszenario:

  1.  Die Kundenfirma **Protomax** hat eine erste Serienproduktion des **NovoXP** Produkts gestartet.
  2.  Die 5 Komponenten des Prototyps können auf N verschiedenen Wegen zusammengesetzt werden
  3.  In m < N dieser Wege sind 1 oder 2 unserer 3-D Drucker involviert (1 realer, mehrere simulierte 3-D Drucker)
  4.  Die NIMBLE.AT Platform erlaubt die allgemeine Definition einer Produktionslogistik
  5.  Das Optimierungsservice **Profactor-FJSSTT** kann von der Platform aus aufgerufen werden, um eine allgemein definierte Produktionslogistik über die verfügbaren Maschinen zu optimieren.
  6.  Wir definieren nun die Produktionslogistik für das NovoXP Produkt und erstellen eine initiale Optimierung über **Profactor-FJSSTT**.
  7.  Als nächsten Schritt simulieren wir den tatsächlichen Produktionslauf und injizieren eine Störung an einem unserer involvierten Drucker.
  8.  Durch diese Störung wird nun eine neue Optimierung nötig, die wieder vom **Profactor-FJSSTT-Service** übernommen wird.
  9.  Auf einem Management-Dashboard sieht der Produktionsleiter von Protomax die Definition, die ursprüngliche Planung, die Störung, und die Neu-Optimierung.

Dieses Szenario wurde um zwei weitere Szenarien erweitert. Mit jeweils 5 Permutationen ergeben sich daraus insgesamt 15 Jobs, die formal in der Datei [Szenarien.md](Szenarien.md) beschrieben sind. Zur Ausführung stehen bis zu 28 Maschinen zur Verfügung. Die Beschreibung der einzelnen Maschinen sowie deren Zuordnung zu den 8 Manufacturing Firms ist in [Maschinen.md](Maschinen.md) verfügbar.
