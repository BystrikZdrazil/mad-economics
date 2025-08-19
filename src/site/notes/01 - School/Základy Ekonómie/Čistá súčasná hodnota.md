---
{"dg-publish":true,"permalink":"/01-school/zaklady-ekonomie/cista-sucasna-hodnota/","tags":["year1","winterSemester","uniZEK"]}
---


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




# Súčasná hodnota
Osviežme si teda výpočet súčasnej hodnoty €100 ktorý obdržíme o jeden rok, pri predpoklade úrokovej sadzby (diskontná sadzba, či výnos obetovanej príležitosti) 5%:

$SH = 100/1.05 = 95.24$

Aká bude súčasná hodnota €100 ktoré obdržíme o dva roky pri nezmenenej úrokovej sadzbe 5%?

$SH = 100/(1.05*1.05) = 100/1.05² = 90.7$

€100 musíme deliť diskontnou sadzbou dva krát, lebo 1.05² (čo je 1.1025) je úroková sadzba za obdobie dvoch rokov, ktorú dostaneme od banky za predpokladu 5% p.a. Keď sme „ročný cash-flow diskontovali ročnou sadzbou (5%), musíme „dvojročný“ cash-flow diskontovať dvojročnou sadzbou (10.25%). V tomto momente je nám jasné, akú hodnotu má cenný papier (či iné aktívum), ktoré nám vygeneruje €100 o rok a €100 o dva roky; €95.24 + €90.7 = €185.94

![](https://www.podnikajte.sk/cached/containers/main/obrazky-v-clankoch/2011-02-08-csh-1.jpg/b936821e99f7e417babe3f5fddce9acd.jpg)

Mohli by sme podobným spôsobom oceňovať aktíva generujúce cash-flow tri, štyri, či viac rokov:

$SH = C1/(1+r) + C2/(1+r)² + C3/(1+r)³ +...$

Túto techniku nazývame **diskontovaný cash-flow**, inak povedané počítame súčasnú hodnotu každého budúceho cash-flow, po čom ich možme jednoducho spočítať. Aby sme sčítavali jablká s jablkami, musíme najprv nájsť hodnotu všetkých cash-flow plynúcich v rôznych obdobiach, v istom čase a až po tom ich sčítať. **V našom prípade môžme povedať, že pri 5% ročnom úroku nám je prakticky jedno či dostaneme € 185.94 dnes alebo € 100 o rok a € 100 o dva roky.**

Vráťme sa k nášmu [skladu z predchádzajúceho článku](https://www.podnikajte.sk/financie/category/finacne-riadenie/article/sucasna-hodnota-penazi.xhtml), do ktorého výstavby sme chceli investovať. Hovorili sme, že cena pozemku na ktorom budeme stavať je €50,000, avšak pri realizácii tohto projektu sa vyskytol problém so stavebným povolením, keďže pozemok sa nachádza na chránenom území. Predpokladajme, že nám všetky povolenia potrebné pre začatie stavby zaberú rok, po ktorom môžeme začať stavať. Stavebné náklady projektujeme na €410,000 a domnievame sa, že o dva roky sklad predáme za €520,000. Napriek tomu, že sme 5% diskontnú sadzbu trošku spochybnili, pre zjednodušenie povedzme, že od podobnej investície očakávame 5% ročný výnos. Diskontná sadzba bude teda 5%.

![](https://www.podnikajte.sk/cached/containers/main/obrazky-v-clankoch/2011-02-08-csh-2.jpg/c750103e7f22957dbbc1526b49f72fbd.jpg)

Vidíme, že pri dnešnej investícii do pozemku €50,000, nákladoch €410,000 ktoré nám vzniknú o rok a príjme €520,000 o dva roky, nám tento projekt vygeneruje čistú súčasnú hodnotu €31,179 (pri diskontnej sadzbe 5%). **Metóda diskontovaných cash-flow je jednou z najčastejšie používaných metód pri oceňovaní investičných projektoch a logika, ktorú sme pred chvílkou použili pri našom imaginárnom projekte, je totožná s logikou používanou pri oceňovaní miliardových investíciách.**

# Perpetuita
**Perpetutita, ako sme už naznačili, je nemenný cash-flow** plynúci do nekonečna. Skúsme si predstaviť hlinené prasiatko, ktore nám každy rok (od budúceho roka do nekonečna) vyprodukuje €100. Akú hodnotu má takéto prasiatko, alebo koľko by ste boli ochotný za takéto prasiatko zaplatiť?

Predpokladajme teda opäť ročný úrok v banke 5%, čiže máme možnosť si svoje [[01 - School/Základy Ekonómie/Peniaze\|Peniaze]] vložiť do banky za tento úrok alebo kúpiť prasiatko. K oceneniu takéhoto prasiatka (aktíva) nám pomôže jednoduchá otázka: „Akú sumu by som musel vložiť do banky, aby mi z tohoto vkladu každý rok plynulo €100?“. Odpoveď na túto otazku je vlastne odpoveďou na našu pôvodnú: „Akú hodnotu má naše prasiatko?“. Hodnota našej perpetuity je teda €2,000. Predstavme si vklad €2,000 do banky pri úroku 5%, pričom s istinou nebudeme hýbať a ročné úroky si zakaždým zoberieme domov. O rok dostaneme úrok €100, ktoré si vyberiem a istinu nechám v banke ďalej pracovať, o dva roky inkasujem opäť €100 atď., až „do nekonečna“. Za prasiatko sme teda ochotní zaplatiť €2,000.

$SH = cash-flow / r (diskontná sadzba)$

Pre náš prípad: SH = €100 / 0.05 = €2,000. Opäť, pri 5% úroku p.a. je nám jedno či dostaneme €2,000 dnes alebo €100 každý rok do nekonečna.

# Anuita
**Anuita je tok nemenného cash-flow, ktorý plynie počas ohraničeného obdobia**. Klasický príklad anuity je hypotéka (ku ktorej sa ešte vrátime), kde platíme fixnú čiastku počas niekoľkých rokov (x 12 mesiacov). Anuita je ale napríklad aj splátka auta, pri tretinovom financovaní, o čom sme hovorili úplne na začiatku našej debaty. Ako na všetko, aj na anuitu máme vzorec, ktorého hlavnou úlohou je, aby nám uľahčil výpočet – namiesto diskontovania povedzme desiatich cash-flow počas 10 rokov, použijeme jednoducho vzorec:

$SH anuity = {1/r – 1/(r(1+r)ª)} * cashflow$

a – počet periód počas ktorých nám plynie cash-flow

Vzorec síce vyzerá zložito, ale memorovať ho netreba, keďže by nám mal život uľahčovať, nie sťažovať. Vysvetlime si teda anuitu pri financovaní auta, pri ktorom zaplatím tretinu ceny o rok, tretinu o dva a tretinu o tri roky. Koľko nás efektívne stojí toto auto? Opäť musíme vypočítať súčasnú hodnotu týchto troch splátok. Znova zopár predpokladov, úrok v banke 5%, cena auta je €21,000, pričom ku koncu každého z nasledujúcich troch rokov zaplatíme €7,000.

![](https://www.podnikajte.sk/cached/containers/main/obrazky-v-clankoch/2011-02-08-csh-3.jpg/bbb37300d1a44041b745715201858f67.jpg)

Presvedčme sa, že vzorec naozaj funguje:

SH = €7,000 \* {1/0.05 – 1/(0.05(1.05³))} = €7,000 \* (20 – 17.28) = €19,062.7

Auto nás teda efektívne stojí €19,063 a díler nám prakticky ponúka zľavu €1,937 takouto možnosťou financovania.

Ďalší praktický príklad anuity zo života je klasická hypotéka. Povedzme, že si chceme zobrať hypoúver vo výške €100,000 a naša banka nám ponúka úrokovú sadzbu 4% pri 30 ročnom splácaní. Aká bude mesačná splátka? Keď sa pozrieme na vzorec, v tomto prípade poznáme SH (€100,000), poznáme úrokovú sadzbu (4% p.a., 0.333% mesačne), poznáme počet periód (30x12=360), nepoznáme ale cash-flow, čiže splátku:

€100,000 = X \* {1/0.00333 – 1/(0.00333(1.00333^360))}  
X = €100,000 / 209.6 = €477.2

Mesačne by sme teda splácali €477.2 a tento krát nám vzorec skutočne pomohol, čo je však podstatné je, že chápeme základnú konštrukciu hypotéky. Súčasná hodnota je výška úveru (€100,000) keďže túto sumu spotrebujeme dnes a tento úver má pri úroku 4% p.a. hodnotu 360 splátok vo výške €477.2 (keby sme diskontovali všetkých 360 splátok do súčasnosti, dostali by sme výšku úveru).

  
*Viktor Lehocký*

*autor je špecialistom na firemné financie*

</div></div>
