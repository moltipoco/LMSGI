# Exercici 3 – Transforma JSON a XML (2 punts)

Tens el document JSON següent. Converteix-lo a un document XML **ben format** que representi
exactament les mateixes dades i relacions.
~~~~
{
"tornei": {
"nom": "Lliga Local de Pàdel 2025",
"temporada": 2025,
"equips": [
{
"id": 10,
"nom": "Raquetes Blaves",
"jugadors": [
{ "dorsal": 1, "nom": "Carles Vidal", "categoria": "A" },
{ "dorsal": 2, "nom": "Marta Puig", "categoria": "B" }
]
},
{
"id": 11,
"nom": "Smash FC",
"jugadors": [
{ "dorsal": 1, "nom": "Jordi Roca", "categoria": "A" },
{ "dorsal": 2, "nom": "Laia Solà", "categoria": "A" },
{ "dorsal": 3, "nom": "Pere Mas", "categoria": "B" }
]
}
]
}
}
~~~~
**Requisits:**
- Element arrel: < tornei >.
- Utilitza **atributs** per als identificadors (id, dorsal) i **subelements** per a la resta de dades.
- El document ha de tenir la declaració < ?xml version="1.0" encoding="UTF-8"? >.

# Solució

[Document XML tornei.xml](./tornei.xml)