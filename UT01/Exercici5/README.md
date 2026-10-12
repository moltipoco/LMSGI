# Exercici 5 – Modela dades jeràrquiques en JSON (2 punts)
Escriu un document JSON **vàlid** (RFC 8259) que representi la informació d'un sistema d'enquestes amb
les característiques següents:

- Hi ha 2 **enquestes**.
- Cada enquesta té:
1. Un id (enter).
2. Un titol (cadena de text).
3. Un activa (booleà).
4. Una llista de preguntes (mínim 2 per enquesta).
- Cada pregunta té:
1. Un ordre (enter, indica la posició).
2. Un text (cadena de text).
3. Un tipus (pot ser "opcio_multiple" o "text_lliure").
4. Si el tipus és "opcio_multiple", ha de tenir una llista opcions amb almenys 3 cadenes de
text.
○ Si el tipus és "text_lliure", no cal el camp opcions.

**Inventa't el contingut** (tema lliure: satisfacció d'un servei, preferències, avaluació, etc.).

**Requisits**:
- JSON vàlid: claus entre cometes dobles, valors numèrics sense cometes, booleans sense cometes.
- Arrel: objecte amb una clau "enquestes" que conté un array

# Solució

[Document JSON enquestes.json](./enquestes.json)