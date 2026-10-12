# Exercici 1 – Correcció d'errors en XML (2 punts)

Els fragments XML següents contenen **errors de format**. Per a cada fragment:
1. Indica **quants errors** hi ha i quins són (descriu-los breument).
2. Escriu la versió **corregida** del fragment.
## Fragment 1.1
~~~~
<?xml version="1.0" encoding="UTF-8"?>
<agenda>
<contacte id=1>
<nom>Pau Ferrer</nom>
<telefon>600 123 456</telefon>
<email>pau@exemple.cat
</contacte>
<Contacte id="2">
<nom>Rita Camps</nom>
<telefon>677 987 654</telefon>
<email>rita@exemple.cat</email>
</contacte>
</agenda>
~~~~
## Fragment 1.2
~~~~
<horari>
<dia nom="Dilluns">
<classe inici="08:00" fi="09:00">Matemàtiques<classe>
<classe inici="09:00" fi="10:00">Anglès</classe>
</dia>
<dia nom=Dimarts>
<classe inici="10:00" fi="11:00">Història</classe>
</dia>
~~~~

# Solucions

## Errores encontrados
- Atributo id=1 no está entre comillas
- tag < email > con contenido pau@example.cat no cerrado
- Contacte no está cerrado y es incorrecto seguiendo la estructura del documento. Tendría que ser < contacte >

## Solución fragmento 1.1
- [Fragment 1.1 agenda](./agenda.xml)

## Errores encontrados
- Atributo nom=Dimarts no está entre comillas
- En la asignatura de matemáticas está mal cerrado el tag < classe inici="08:00" fi="09:00">Matemàtiques< classe >. 
Tendría que ser < /classe >
## Solución fragmento 1.2
- [Fragment 1.2 horari](./horari.xml)