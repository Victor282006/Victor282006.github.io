[Homepage](index.md)

# Diagrame de _lowchart_

```mermaid
flowchart LR
A[Anul I] --> B[Anul II]
```

```mermaid
flowchart LR
A(Anul I) --> B(Anul II)
```

**De retinut:**
- Diagramele _flowchart_ au noduri si conectori
- Nodurile au:
  - forma (data de parantezele folosite la descrierea _nodului_)
  - ID (sirul folosit in afara descrierii nodului)
  - Descriere (textul ce apare in caseta nodului si care este implementat in interiorul diferielor tipuri de paranteze - ce decid forma casetei nodului)
- Conectorii au:
  - diferite tipuri de sageti sau chiar pot activa fara sageti
  - diferite tipuri de linii:
    -`-->`linii continua (sageata dreapta)
    -`--`line continua (fara sageti)
    -`<-->`linie continua (sageata stanga si sageata dreapta)
    -linie continua (linie ingrosata)

  ## Diagrama _flowchart_ avansate

```
A--> B & C & D & E
```


