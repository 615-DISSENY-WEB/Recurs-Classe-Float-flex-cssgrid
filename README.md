# Laboratori de CSS: Flexbox, Grid i float

Recurs en català per a DAW. Obre **index.html** al navegador: no cal instal·lar dependències ni iniciar cap servidor.

## Objectius i prerequisits

Cal conèixer l’estructura bàsica d’HTML, classes i selectors CSS. En acabar, l’alumnat ha de poder triar Flexbox o Grid, distingir propietats de pares i fills, construir layouts adaptables i comprovar-los amb contingut real i teclat.

## Nivell inicial

Començar pel significat de pare, fill i `>` (fill directe), amb exemples petits. Treballar `display`, `gap`, direcció, alineació, `flex-wrap`, columnes i àrees. Les ampliacions de Grid per línies amb nom i el projecte poden deixar-se per a una segona sessió.

## Itinerari

| Fitxer | Contingut |
| --- | --- |
| index.html | Índex, mètode de treball i eines del navegador |
| fonaments.html | Pares i fills, selector >, model de caixa i gap |
| flexbox1.html | Eixos, alineació i laboratori interactiu |
| flexbox2.html | Files, gap i salt de línia amb wrap |
| cssgrid.html | Tres columnes, fr i files implícites |
| cssgrid1.html | Posicionament per línies i span |
| cssgrid2.html | Línies amb nom i grid-area |
| cssgrid3.html | Àrees amb nom i media queries |
| responsive.html | Comparació de files i columnes; canvi senzill amb @media |
| projecte.html | Agenda de tallers amb Grid i Flexbox |
| float.html | Text envoltant imatges i menú històric |

## Organització

- `assets/css/base.css`: presentació comuna, tipografia, focus, caixes i targetes.
- `assets/css/style.css`: regles didàctiques, agrupades per lliçó; fitxer principal per experimentar.
- `assets/js/laboratori.js`: controls opcionals de Flexbox i visualització del CSS. La resta del recurs funciona sense JavaScript.
- `assets/img/`: imatges locals originals; no es necessiten serveis externs.

Cada lliçó inclou objectiu, demostració, codi, repte i solució desplegable. Els fragments destaquen les regles del concepte, mentre que els fitxers CSS contenen els estils complets. El laboratori interactiu modifica estils temporals: recarregar restaura els valors inicials.

## Proposta de treball a l’aula

1. Fonaments i eixos: predir què canviarà abans de tocar una propietat.
2. Flexbox: posar elements en fila, separar-los i permetre el salt de línia.
3. Grid: construir la mateixa disposició amb línies numèriques, noms i àrees.
4. Adaptació: reduir el viewport i justificar quan cal una media query.
5. Projecte: dibuixar contenidors, implementar i defensar les decisions.

En cada bloc: observar → predir → modificar → comprovar → explicar. Fer servir les superposicions Flex/Grid de l’inspector.

## Avaluació del projecte

- 30%: elecció i explicació de Flexbox/Grid i propietats de pare/fill.
- 30%: adaptació a 320, 768 i 1280 px, textos llargs i quantitats variables de targetes.
- 20%: semàntica, ordre de lectura, teclat, focus, imatges i zoom al 200%.
- 20%: jerarquia visual, llegibilitat, espaiat i codi entenedor.

Comprovar que la pàgina no tingui desbordament horitzontal. Els blocs de codi poden tenir desplaçament propi. Les lliçons de línies mantenen expressament tres columnes; la lliçó d’àrees mostra l’evolució adaptable.

## Referències

- [Flexbox a MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout/Basic_concepts)
- [Grid a MDN](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Grids)
- [Relació entre Flexbox i Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout/Relationship_with_other_layout_methods)
