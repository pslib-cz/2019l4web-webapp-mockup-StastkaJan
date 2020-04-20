# Cure
Zachraňte celé lidstvo! Zabraňte viru uniknout!

## Pravidla
- velikost hrací desky je 10x10 políček
- jsou dva hráči - virus a cure (lék)
### Virus - řízen počítačem (class="virus" na td tagu tabulky)
- může se objevit náhodně, ale vždy minimálně 3 políčka od kraje (stačí v jedné z prostředních polí)
- má za úkol uniknout z hrací plochy, toho docílí tak, že se dotkne kraje hrací desky
- pohybuje se o jedno pole vertikálně či horizontálně z jakékoli své buňky (nesmí se pohybovat digitálně!)
- jeho políčko je značeno symbolem viru (class="virus" na td tag)
### Cure (lék) - řízen hráčem (class="cure" na td tagu tabulky)
- má za úkol zabránit uniknutí virusu, toho docílí tak, že zamezí virusu všechny možnosti pohybu aniž by se virus dotkl kraje hrací desky
- kliknutím může zabrat svá pole kdekoli chce (může své políčka položit kdekoli chce)
- jeho políčko je značeno symbolem léku (class="cure" na td tag)
### Konec hry
- po skončení hry se přidá na "body > div.result" class="loose" (prohra) nebo class="win" (výhra)

## Seznam class
- virus - políčko viru (na <td> prvek tabulky)
- cure - políčko léku (na <td> prvek tabulky)
- loose - prohra (na <div class="result>)
- win - výhra (na <div class="result>)

## Cíl
Cílem hráče je zabránit viru uniknout.
