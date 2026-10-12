# Exercici 4 – Amplia un document XML (2 punts)

Tens el document XML següent, que representa un inventari d'una botiga de plantes:
~~~~
<?xml version="1.0" encoding="UTF-8"?>
<inventari>
<planta id="PLT-01">
<nom>Monstera deliciosa</nom>
<tipus>Interior</tipus>
<preu moneda="EUR">24.99</preu>
</planta>
<planta id="PLT-02">
<nom>Roser miniatura</nom>
<tipus>Exterior</tipus>
<preu moneda="EUR">12.50</preu>
</planta>
</inventari>
~~~~
Fes les **quatre modificacions** següents sobre el document (entrega la versió final completa):
1. **Afegeix** un atribut estoc="disponible" a cada element <planta>.
2. **Afegeix** un subelement <regs> dins de cada <planta> amb el text "2 cops per setmana" (PLT-01)
i "3 cops per setmana" (PLT-02).
3. **Afegeix** una tercera planta amb les dades: id PLT-03, nom Cactus saguaro, tipus Interior, preu
8.75 EUR, regs "1 cop per setmana", estoc "sota comanda".
4. **Afegeix** a l'element arrel < inventari > un atribut actualitzat="2025-05-01"

#Solució

[Document XML inventari](./inventari.xml)