Ho provato a creare un progetto con 3 moduli (3 microservizi Spring).  
I primi 2 come progetti Intellij dentro una cartella creata da me ("microservizi-multipli").  
Poi con Intellij ho aperto la cartella "microservizi-multipli" e Intellij ha creato la sua cartella ".idea".  
Il terzo progetto l'ho creato all'interno del progetto "microservizi-multipli" facendo:
> tasto destro sulla project root  
> New  
> Module..  
> Spring  

In quest'ultimo caso Intellij non crea la cartella ".idea" nel progetto "microservizio3".  
Tutti e 3 i progetti sono riconosciuti da Maven e Spring all'interno del progetto "microservizi-multipli" su Intellij.  
Il versioning con git è facilmente gestibile dal progetto root.  