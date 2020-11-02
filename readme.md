README.md

Til þess að keyra verkefnið:\
npm install\
Run: npm run dev\
npm run lint er til staðar

Script lýsing:
Skriptan "npm run dev" keyrir sass og browser sync. Þeim er gert kleift að keyra samtímis með concurrently. "npm run lint" hefur
villuleit á scss skrám með stylelint-config-standard og stylelint-config-sass-guidelines að leiðarljósi.


Settum lang=en í stað lang=is þar sem enginn íslenska kemur fram í beint í html.
Þetta var gert í nafni W3C Validator.

Verkefninu er skipt þannig allar myndir eru í img möppu.
í node_modules er allt sem þarf til að keyra verkefnið,
en til að sú mappa sé til staðar þarf að keyra npm install.
Scss skjöl eru að finna í styles möppunni sem er inni í Hverk1-vef1. Þar eru einnig html skjölin, auk readme og package
JSON skránna, geymd.

CSS skjal er búið til út frá scss skjölum þegar skipunin nmp run sass
er keyrð. Það á einnig að gerast að sjálfu sér þegar breytingar eru
vistaðar í styles.scss skránni. SCSS skjölum er skipt þannig hvert og eitt hefur sérhæft og afmarkað hlutverk.

Til að gera recipe.html aðgengilegt þá settum við vísun á þá síðu í gegnum "About us" í header.

Keyrðum html í gegnum axe og villurnar sem voru þar eru vegna þess að litamismunur er lítill,
breyttum því ekki þar sem það er hluti af gefinni hönnun.

Þeir sem unnu verkefnið:

Daníel Helgi Ágústsson, hí notendanafn: dha7, github notendanafn: dha7\
Oddur Áskell Thoroddsen, hí notendanafn: oat3, github notendanafn: Culmenus\
Tristan Freyr Jónsson, hí notendanafn tfj2, github notendanafn: tfj2
