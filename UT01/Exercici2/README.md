# Exercici 2 – Escriu XML a partir d'una descripció (2 punts)

Escriu un document XML **ben format** que representi la informació següent. **No** et donen el codi; l'has de
crear tu tot partint de zero.

**Descripció**:

Un **catàleg de pel·lícules** d'una plataforma de streaming conté tres pel·lícules. Cada pel·lícula té:
- Un **identificador únic** (atribut).
- Un **títol**.
- L'**any** d'estrena (valor enter). 
- El **gènere** (per exemple: drama, comèdia, acció).
- La **durada** en minuts, amb una unitat explícita (atribut unitat="min").
- Una llista de fins a tres **actors** principals (cada actor és un subelement amb nom i cognoms).

**Dades de les pel·lícules**:

|ID|Títol|Any|Gènere|Durada(min)|Actors principals|
|--|--|--|--|--|--|
|P01|El laberint del faune|2006|Fantasia|118|Ivana Baquero, Sergi López|
|P02|Societat Morta|1989|Drama|128|Robin Williams, Ethan Hawke,Robert Sean Leonard|
|P03|Interstellar|2014|Ciència-ficció|169|Matthew McConaughey, Anne Hathaway|

**Requisits**:
- Element arrel:<cataleg> .
- Document ben format (declaració XML, un sol arrel, tancaments correctes, cometes als atributs).
- Utilitza noms d'etiquetes descriptius en català o anglès, però coherents.

# Solució

[Document XML Catàleg](./cataleg.xml)