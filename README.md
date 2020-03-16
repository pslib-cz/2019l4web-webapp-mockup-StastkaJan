# Cure
Zachraňte celé lidstvo! Zabraňte viru uniknout!

## Pravidla
- velikost hrací desky je 10x10 políček
- jsou dva hráči - virus a cure (lék)
### Virus - řízen počítačem (class="virus" na prvku tabulky)
- může se objevit náhodně, ale vždy minimálně 3 políčka od kraje
- má za úkol uniknout z hrací plochy, toho docílí tak, že se dotkne kraje hrací desky
- pohybuje se o jedno pole vertikálně či horizontálně z jakékoli své buňky (nesmí se pohybovat digitálně!)
- jeho políčko je značeno symbolem viru (class="virus")
### Cure (lék) - řízen hráčem (class="cure" na prvku tabulky)
- má za úkol zabránit uniknutí virusu, toho docílí tak, že zamezí virusu všechny možnosti pohybu aniž by se virus dotkl kraje hrací desky
- kliknutím může zabrat svá pole kdekoli chce (nemusí se jakkoli dotýkat)
- jeho políčko je značeno symbolem léku (class="cure")
### Konec hry
- po skončení hry se přidá na aside class="loose" pro prohru nebo class="win" pro výhru

## Cíl
Cílem hráče je zabránit viru uniknout.
