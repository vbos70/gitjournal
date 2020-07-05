---
created: 2020-07-04T17:07:15+03:00
modified: 2020-07-05T10:25:28+03:00
title: markdown
---

##   Tekststijlen

Dit 

``` 
**vet**
_cursief_
~~doorstreept~~
```

Geeft

**vet**
_cursief_
~~doorgestreept~~

## Lijsten

Start de eerste regel van de lijst op een nieuwe regel, uitgelijnd volgens de context. Start elk onderwerp met `*`, `-` of `+` symbool uitgelijnd recht onder hetzelfde symbool op de vorige regel. Maak lijsten in lijsten door regels
in te springen en een ander  symbool te gebruiken.

Dit

```
- eerste 
- tweede
  + tweede - eerste 
     * tweede - eerste - eerste 
  + tweede - tweede
  + tweede - derde 
     * tweede - derde - eerste 
- derde 
- laatste 
```

Geeft

- eerste (-)
- tweede (-)
  - tweede - eerste (- -)
  * tweede - tweede (* -)
  - tweede - derde (- -)
* derde (*)
* laatste (*)

## Links

Zie ook [github markdown guide](https://guides.github.com/features/mastering-markdown/)