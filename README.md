# Creiamo un 'piccolo' giornale online

## Wireframe
https://www.figma.com/file/0gGEoY1QkbXmtIBgUnTZkN/LaBooleana?node-id=0%3A1


## Avremo due tipi di utenti: 
1. registrati 
1. guests

## Tutti gli utenti registrati possono: 
1. inserire: categorie, tag e articoli
1. modificare e cancellare i propri elementi
1. vedere gli articoli degli altri
1. vedere e usare le categorie e i tag degli altri

## Tutti gli utenti registrati non possono: 
1. cancellare o modificare elementi creati da altri utenti

## Gli utenti guest possono:
vedere gli articoli pubblicati

---

### Relazioni Entità
1. Un **utente** può avere tante **categorie**, **articoli** e **tags**
1. Una **categoria** può avere tanti **articoli**
1. Un **articolo** può avere una sola **categoria**
1. Un **articolo** può avere tanti **tags**
1. Un **tag** può avere tanti **articoli**

