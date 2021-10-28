# Hópverkefni 1

Þetta verkefni var gert af Hermanni, Helga og Bynjari. Síðan er byggð á hönnun eftir Óþekktan hönnuð (https://www.figma.com/file/FjymA3lRoi49h83WgAccEw/H%C3%B3pverkefni-1?node-id=0%3A1) og síða er heimasíða fyrir tæknibúðina.

## Keyrsla verkefnis
- `npm run dev`: keyrir verkefnið og opnar síðuna í nýjum vafra, ásamt því að fylgjast með breytingum sem gerðar eru á scss-inu og sýna þær strax.
- `npm run lint`: keyrir kóða verkefnisins í gegnum stylelint sem eru staðlar fyrir uppsetningu css og scss kóða.
- https://hopverkefni1.netlify.app/ Hér er linkur á síðuna uppsetta á netlify.

## Lýsing verkefnisins

Verkefninu er skipt upp í 4 síður. Fyrst þegar þú kemur á síðuna sérðu forsíðuna og þaðan er hægt að komast á 3 undirsíður með meiri upplýsingum. Síðurnar eru eftirfarandi:

- Forsíða
- Vörulisti
- Vara
- pöntunarsíða

### Uppsetning 

Verkefnið er unnið í HTML og CSS, þar sem CSS hlutinn er útfærður með SCSS. Í litlum hluta verkefnins notast við Javascript.

Í verkefna möppu eru 9 skrár, ásamt 5 möppum en við ætlum að horfa framhjá tveimur þeirra. `/styles` mappan okkar inniheldur 13 scss skrár sem eru grundvallaratriði CSS kóðans í verkefninu. Möppurnar eru eftirfarandi:


- `config.scss` - Hér eru breytur sem notaðar eru í verkefninu
- `dropdown_menu.scss` - Hamborgara valmyndin
- `fonts.scss` - Letur og leturgerðir
- `footer.scss` - Fóturinn á öllum síðum verkefnis
- `frontpage-content.scss` - SCSS skjal fyrir efnið á forsíðunni
- `frontpage-products.scss` - SCSS skjal fyrir vörurnar á forsíðunni
- `frontpage-triangles.scss` - Býr til halla á myndirnar á forsíðunni
- `header.scss` - Hausinn á öllum síðunum
- `layout.scss` - Grid layout fyrir allar síðurnar
- `orderpage-content.scss` - SCSS skjal fyrir pöntunarsíðuna
- `product-card.scss` - SCSS skjal fyrir öll vöruspjöld verkefnisins
- `product-page-content.scss` - SCSS skjal fyrir vörusíðuna
- `productlist-page-content.scss` - SCSS skjal fyrir vörulistasíðuna

>Þessi skjöl eru keyrð í gegnum `styles.scss` sem er aðal scss skjalið og útfrá því verður `styles.css` til.

Annað sem fram kemur í verkefnamöppu eru skjöl eins og `package.json` sem er með allar scriptur og dependencies verkefnisins og `/img` mappan sem inniheldur allar myndir sem notaðar eru í verkefninu.

## Hópmeðlimir
### Hermann
    - Netfang: hoh36@hi.is
    - Github: `hemmiklemmi`

### Brynjar
    - Netfang: brb83@hi.is
    - Github: `brynjar13`

### Helgi
    - Netfang: hea40@hi.is
    - Github: `HelgiAlmarsson`
