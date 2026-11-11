# Exercici 2 – Aplica un disseny CSS a una pàgina ja estructurada (3 punts)
Se't proporciona la següent pàgina HTML ja feta (no la pots modificar, excepte per afegir
l'atribut class als elements que ho necessitin). La teva tasca és crear l'arxiu css/estil.css per tal
que el resultat visual s'assembli el màxim possible al disseny descrit a continuació.
Codi HTML de partida (copia'l tal qual a index.html)
~~~
<!doctype html>
<html lang="ca">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<meta name="description" content="Blog sobre viatges per Catalunya." />
<title>Viatges per Catalunya</title>
<link rel="stylesheet" href="css/estil.css" />
</head>
<body>
<header>
<h1>Viatges per Catalunya</h1>
<nav>
<ul>
<li><a href="#">Inici</a></li>
<li><a href="#">Rutes</a></li>
<li><a href="#">Contacte</a></li>
</ul>
</nav>
</header>
<main>
<article>
<h2>La Vall de Boí</h2>
<p>Un conjunt romànic Patrimoni de la Humanitat envoltat de natura espectacular.</p>
</article>
<article>
<h2>El Delta de l'Ebre</h2>
<p>Parc natural amb arrossars, llacunes i una rica biodiversitat d'aus.</p>
</article>
<article>
<h2>El Montseny</h2>
<p>Reserva de la Biosfera amb boscos centenaris i cims que superen els 1.700 m.</p>
</article>
</main>
<aside>
<h2>Consells de viatge</h2>
<ul>
<li>Reserva l'allotjament amb antelació.</li>
<li>Porta roba d'abric a la muntanya.</li>
<li>Respecta el medi natural.</li>
</ul>
</aside>
<footer>
<p>&copy; 2025 Viatges per Catalunya</p>
</footer>
</body>
</html>
~~~
Descripció del disseny que has d'aconseguir
┌─────────────────────────────────────────────────────────────
┐
│ CAPÇALERA fosca (fons #2c3e50, text blanc)
 │
│ Títol a l'esquerra · Navegació horitzontal a la dreta
 │
├──────────────────────────────────┬──────────────────────────
┤
│ MAIN (70% amplada)
 │ ASIDE (28% amplada)
 │
│ ┌──────────────────────────┐ │ Fons #ecf0f1
 │
│ │ Article (fons blanc, │ │ Títol en verd fosc
 │
│ │ ombra suau, vora
 │ │ Llista amb punts de
 │
│ │ esquerra de 4px #27ae60)│ │ color #27ae60
 │
│ └──────────────────────────┘ │
 │
│ (Repetit per als 3 articles) │
 │
├──────────────────────────────────┴──────────────────────────
┤
│ FOOTER centrat (fons #2c3e50, text gris clar)
 │
└─────────────────────────────────────────────────────────────
┘
Requisits del CSS:
1. Layout principal amb Flexbox (main + aside en fila).
2. La capçalera usa Flexbox per separar títol i navegació (justify-content: space-between).
3. Els <article> han de tenir vora esquerra de 4 px en color #27ae60, fons blanc i ombra
(box-shadow).
4. Efecte hover als enllaços de navegació (canvi de color o subratllat).
5. Posa comentaris al CSS per explicar cada secció.
6. Estructura de fitxers: index.html i css/estil.css.
7. En lliurar, adjunta una captura de pantalla de la pàgina renderitzada.

# Solución

[original.html](./original.html)
[estil.css](./estil.css)