# TCP-BasisServer

-----------------
Java Client+Server
-----------------

Environment des TCP-Servers:
   - storage (Verzeichnis) für zu speichernde Files
   - Port: 18769

Funktionalität:
 - info: liefert folgende Info als String zurück: OS (Version), JVM (Version), verfügbares MEM der JVM
 - store fn: sichert den File "fn" im Verzeichnis storage
 - list:      listet alle im Verzeichnis storage gefunden Files auf (nur die Namen)
 - get fn:    liefert den File mit dem Namen fn aus (d.h. wird am Client dann abgespeichert
