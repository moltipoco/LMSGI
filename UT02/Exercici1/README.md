# Exercici 1 – Detecta i corregeix errors HTML (3 punts)

El codi HTML següent conté 12 errors deliberats (etiquetes mal tancades, atributs incorrectes,
estructura semàntica deficient, metadades absents, etc.). La teva tasca és:
1. Identificar cada error i explicar-lo breument (en un comentari o en un apartat apart del
   PDF).
2. Lliurar el codi corregit i complet, que s'ha de validar sense errors al W3C Validator.
   <!doctype HTML>
~~~
<html>
<head>
<meta name="viewport" content="width=device-width">
<title>Receptes de cuina
</head>
<body>
<header>
<h1>Les millors receptes</h1>
<h1>Cuina casolana i tradició</h1>
</header>
<section>
<h2>Ingredients de la paella</h2>
<ul>
<li>Arròs
<li>Pollastre</li>
<li>Tomàquet</li>
</ul>
</section>
<figure>
<img src="imatges/paella.jpg" width="400">
<figcaption>
</figure>
<section>
<h2>Passos de preparació</h2>
<ol>
<li>Sofregir el pollastre.</lI>
<li>Afegir el tomàquet.</li>
<li>Incorporar l'arròs i el brou.</li>
</ol>
</section>
<a href=https://www.receptes.cat target="_blank">Més receptes</a>
<footer>
<p>Autora: Maria García · 2025<p>
</footer>
</html>
~~~
# Solución
Listado de errores:
1. Etiqueta \<!DOCTYPE html>incorrecta con mayúsculas intercambiadas. Aunque la etiqueta DOCTYPE y su sufijo html no distingue
    entre mayúsculas/minúsculas considero un pequeño error ponerlas con la mayúsculas/minusculas incorrectamente.
2. En el \<head> la etiqueta \<title> no está cerrada.
3. En el \<head> falta la etiqueta \<meta charset="utf-8"/>
4. En el \<head> la etiqueta \<meta name="viewport" no está bien definida y falta cerrarla.
5. Falta la etiqueta \<meta description=""/>
6. No existe el elemento semántico \<main>\</main>. Añadido.
7. En el \<ul> la etiqueta con texto Arròs en el \<li> no está cerrada.
8. En el \<figure> dentro de la etiqueta \<img falta el atributo alt="paella".
9. En el \<figure> el \<figcaption> no está cerrado. Añadido contenido y desdoblado en \<figcaption>Paella\</figcaption>
10. En el \<footer> el \<p> no está cerrado correctamente.
11. La etiqueta \<body> no está cerrada. 
12. En la etiqueta \<html> falta el código del idioma
