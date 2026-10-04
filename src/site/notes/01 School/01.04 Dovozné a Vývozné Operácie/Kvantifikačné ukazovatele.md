---
{"dg-publish":true,"permalink":"/01-school/01-04-dovozne-a-vyvozne-operacie/kvantifikacne-ukazovatele/","tags":["year3","winterSemester","uniDVO"],"dg-note-properties":{"Date":"2026-09-24","Schoolyear":3,"Semester":"Winter","Class":"Import and Export Operations","tags":["year3","winterSemester","uniDVO"]}}
---

# Jednofaktorové infikátory hodnotenia
Jednoduché indexy zavedené na základe teórii jednotlivých ekonómov

- Index odhalených komparatívnych výhod (*RCA*)
- Index obchodnej intenzity (*ITI*)
- Index vnútroodvetvového obchodu (*IIT, GL index*)
- Index obchodnej komplementarity (*ITT*)
- Index podobnosti
- *A ďalšie*

## Identifikácia RCA podla [[01 School/01.06 Európska Únia/Stupne integrácie podľa B. Balassu\|Balassu]]
**RCA > 1 = existencia komparatívnych výhod** krajiny pri exporte v danej komoditnej skupine

**RCA < 1 = ide o komparatívnu nevýhodu** krajiny pri exporte v danej komoditnej skupine

Z Ballasovho indexu teda môžeme
- Posúdiť, či konkrétna krajina vykazuje v danej komodite odhalení komparatívnu výhodu alebo nevýhodu
- Porovnávať výhody jednotlivých komodít danej krajiny, ako aj výhod danej komodity naprieč všetkými krajinami

Intenzita hodnoty indexu RCA (*I*) sa dá rozdeliť do 4 kategórii

0 < RCA <= 1 — **žiadna komparatívna výhoda**
1 < RCA <= 2 — **slabá komparatívna výhoda**
2 < RCA <= 4 — **stredne silná komparatívna výhoda**
4 < RCA — **silná komparatívna výhoda**

![Pasted image 20260930091707.png](/img/user/06%20Images/Pasted%20image%2020260930091707.png)
### Logaritmická forma
**RCAi2 > 0** indikuje existenciu odhalenej komparatívnej výhody v danej tovarovej skupine a jeho veľkosť poukazuje na intenzitu tejto výhody

**RCAi2 < 0** naznačuje nevýhodnosť odhalenej komparatívnej výhody v danej skupine tovaru

![Pasted image 20260930091841.png](/img/user/06%20Images/Pasted%20image%2020260930091841.png)

### Index RCA (3)
Rozdiel indexu relatívne exportných výhod (*RXA*) a relatívne importných výhod (*RMA*)

$$
RXA_{ia} = \left(\frac{X_{ia}}{\sum X_{ia}}\right) / \left(\frac{X_{iw}}{\sum X_{iw}}\right)
$$

$$
RMA_{ia} = \left(\frac{M_{ia}}{\sum M_{ia}}\right) / \left(\frac{M_{iw}}{\sum M_{iw}}\right)
$$
## Index Vnútroodvetvového obchodu
- Najčastejšie vyjadrený **Grubel-Lloyd index** (*GL*)
- Charakterizuje a analyzuje obchod z odvetvovej charakteristiky obchodu

$$
GL_{k}^{ij} = 1 - \frac{|X_{k}^{ij} - M_{k}^{ij}|}{X_{k}^{ij} + M_{k}^{ij}}
$$

* $X_{k}^{ij}$ – export komodity $k$ krajiny $i$ do krajiny $j$
* $M_{k}^{ij}$ – import komodity $k$ z krajiny $j$ do krajiny $i$

- **Interval** výsledných hodnôt je **<0;1>**
- **GL = 0** znamená, že krajina je čistým dovozcom alebo vývozcom, teda nei je prítomný vnútroodvetvových obchod
- **GL = 1** znamená, že existuje vnútroodvetvových obchod medzi krajinami

## Index obchodnej intenzity
$$
TII_{ij} = \frac{x_{ij} / X_{it}}{x_{wj} / X_{wt}}
$$

* $x_{ij}$ – hodnota exportu prvej krajiny do druhej krajiny;
* $x_{wj}$ – hodnota celkových exportov prvej krajiny do celého sveta;
* $X_{it}$ – hodnota svetových exportov do druhej krajiny;
* $X_{wt}$ – celková hodnota svetových exportov.

- TII obsahuje hodnoty od 0 do +∞
- Ak je index **väčší ako 1**, tak to poukazuje o **vysokej** obchodnej výmene medzi skúmanými krajinami
- Ak je index **menší ako 1**, tak to poukazuje o **nízkej** obchodnej výmene medzi skúmanými krajinami

> [!info]
> Závisí od podpísaných vzájomných obchodných dohôd a bariér

### TII medzi krajinami strednej Ázie (*2008 - 2017*)
```chartsview
type: Line
data:
  - year: "2008"
    value: 0.38
    category: "TII SR-Kazachstan"
  - year: "2009"
    value: 0.35
    category: "TII SR-Kazachstan"
  - year: "2010"
    value: 0.34
    category: "TII SR-Kazachstan"
  - year: "2011"
    value: 0.45
    category: "TII SR-Kazachstan"
  - year: "2012"
    value: 0.41
    category: "TII SR-Kazachstan"
  - year: "2013"
    value: 0.51
    category: "TII SR-Kazachstan"
  - year: "2014"
    value: 0.66
    category: "TII SR-Kazachstan"
  - year: "2015"
    value: 0.35
    category: "TII SR-Kazachstan"
  - year: "2016"
    value: 0.12
    category: "TII SR-Kazachstan"
  - year: "2017"
    value: 0.21
    category: "TII SR-Kazachstan"

  - year: "2008"
    value: 0.23
    category: "TII SR-Uzbekistan"
  - year: "2009"
    value: 0.16
    category: "TII SR-Uzbekistan"
  - year: "2010"
    value: 0.29
    category: "TII SR-Uzbekistan"
  - year: "2011"
    value: 0.32
    category: "TII SR-Uzbekistan"
  - year: "2012"
    value: 0.19
    category: "TII SR-Uzbekistan"
  - year: "2013"
    value: 0.31
    category: "TII SR-Uzbekistan"
  - year: "2014"
    value: 0.32
    category: "TII SR-Uzbekistan"
  - year: "2015"
    value: 0.25
    category: "TII SR-Uzbekistan"
  - year: "2016"
    value: 0.12
    category: "TII SR-Uzbekistan"
  - year: "2017"
    value: 0.12
    category: "TII SR-Uzbekistan"

  - year: "2008"
    value: 0.16
    category: "TII SR-Kirgizsko"
  - year: "2009"
    value: 0.17
    category: "TII SR-Kirgizsko"
  - year: "2010"
    value: 0.17
    category: "TII SR-Kirgizsko"
  - year: "2011"
    value: 0.15
    category: "TII SR-Kirgizsko"
  - year: "2012"
    value: 0.09
    category: "TII SR-Kirgizsko"
  - year: "2013"
    value: 0.07
    category: "TII SR-Kirgizsko"
  - year: "2014"
    value: 0.07
    category: "TII SR-Kirgizsko"
  - year: "2015"
    value: 0.05
    category: "TII SR-Kirgizsko"
  - year: "2016"
    value: 0.07
    category: "TII SR-Kirgizsko"
  - year: "2017"
    value: 0.04
    category: "TII SR-Kirgizsko"

  - year: "2008"
    value: 0.04
    category: "TII SR-Tadžikistan"
  - year: "2009"
    value: 0.07
    category: "TII SR-Tadžikistan"
  - year: "2010"
    value: 0.13
    category: "TII SR-Tadžikistan"
  - year: "2011"
    value: 0.05
    category: "TII SR-Tadžikistan"
  - year: "2012"
    value: 0.04
    category: "TII SR-Tadžikistan"
  - year: "2013"
    value: 0.09
    category: "TII SR-Tadžikistan"
  - year: "2014"
    value: 0.04
    category: "TII SR-Tadžikistan"
  - year: "2015"
    value: 0.07
    category: "TII SR-Tadžikistan"
  - year: "2016"
    value: 0.08
    category: "TII SR-Tadžikistan"
  - year: "2017"
    value: 0.02
    category: "TII SR-Tadžikistan"

  - year: "2008"
    value: 0.11
    category: "TII SR-Turkménsko"
  - year: "2009"
    value: 0.18
    category: "TII SR-Turkménsko"
  - year: "2010"
    value: 0.12
    category: "TII SR-Turkménsko"
  - year: "2011"
    value: 0.11
    category: "TII SR-Turkménsko"
  - year: "2012"
    value: 0.08
    category: "TII SR-Turkménsko"
  - year: "2013"
    value: 0.12
    category: "TII SR-Turkménsko"
  - year: "2014"
    value: 0.06
    category: "TII SR-Turkménsko"
  - year: "2015"
    value: 0.09
    category: "TII SR-Turkménsko"
  - year: "2016"
    value: 0.04
    category: "TII SR-Turkménsko"
  - year: "2017"
    value: 0.06
    category: "TII SR-Turkménsko"
options:
  xField: "year"
  yField: "value"
  seriesField: "category"
  color:
    - "#3b62b0"
    - "#e07834"
    - "#9c9c9c"
    - "#f0bd24"
    - "#569bd5"
  smooth: false
  point:
    size: 3
    shape: "circle"
  yAxis:
    min: 0
    max: 0.70
    tickInterval: 0.10
```

### TII medzi krajinami strednej Ázie a SR (*2008 - 2017*)
```chartsview
type: Line
data:
  - year: "2008"
    value: 0.09
    category: "TII Kazachstan-SR"
  - year: "2009"
    value: 0.05
    category: "TII Kazachstan-SR"
  - year: "2010"
    value: 0.11
    category: "TII Kazachstan-SR"
  - year: "2011"
    value: 0.08
    category: "TII Kazachstan-SR"
  - year: "2012"
    value: 0.05
    category: "TII Kazachstan-SR"
  - year: "2013"
    value: 0.05
    category: "TII Kazachstan-SR"
  - year: "2014"
    value: 0.02
    category: "TII Kazachstan-SR"
  - year: "2015"
    value: 0.03
    category: "TII Kazachstan-SR"
  - year: "2016"
    value: 0.05
    category: "TII Kazachstan-SR"
  - year: "2017"
    value: 0.04
    category: "TII Kazachstan-SR"

  - year: "2008"
    value: 0.28
    category: "TII Uzbekistan-SR"
  - year: "2009"
    value: 0.06
    category: "TII Uzbekistan-SR"
  - year: "2010"
    value: 0.01
    category: "TII Uzbekistan-SR"
  - year: "2011"
    value: 0.01
    category: "TII Uzbekistan-SR"
  - year: "2012"
    value: 0.00
    category: "TII Uzbekistan-SR"
  - year: "2013"
    value: 0.01
    category: "TII Uzbekistan-SR"
  - year: "2014"
    value: 0.01
    category: "TII Uzbekistan-SR"
  - year: "2015"
    value: 0.01
    category: "TII Uzbekistan-SR"
  - year: "2016"
    value: 0.03
    category: "TII Uzbekistan-SR"
  - year: "2017"
    value: 0.01
    category: "TII Uzbekistan-SR"

  - year: "2008"
    value: 0.00
    category: "TII Kirgizsko-SR"
  - year: "2009"
    value: 0.00
    category: "TII Kirgizsko-SR"
  - year: "2010"
    value: 0.00
    category: "TII Kirgizsko-SR"
  - year: "2011"
    value: 0.00
    category: "TII Kirgizsko-SR"
  - year: "2012"
    value: 0.08
    category: "TII Kirgizsko-SR"
  - year: "2013"
    value: 0.00
    category: "TII Kirgizsko-SR"
  - year: "2014"
    value: 0.00
    category: "TII Kirgizsko-SR"
  - year: "2015"
    value: 0.00
    category: "TII Kirgizsko-SR"
  - year: "2016"
    value: 0.04
    category: "TII Kirgizsko-SR"
  - year: "2017"
    value: 0.01
    category: "TII Kirgizsko-SR"

  - year: "2008"
    value: 0.42
    category: "TII Tadžikistan-SR"
  - year: "2009"
    value: 0.00
    category: "TII Tadžikistan-SR"
  - year: "2010"
    value: 0.00
    category: "TII Tadžikistan-SR"
  - year: "2011"
    value: 0.00
    category: "TII Tadžikistan-SR"
  - year: "2012"
    value: 0.00
    category: "TII Tadžikistan-SR"
  - year: "2013"
    value: 0.00
    category: "TII Tadžikistan-SR"
  - year: "2014"
    value: 0.00
    category: "TII Tadžikistan-SR"
  - year: "2015"
    value: 0.02
    category: "TII Tadžikistan-SR"
  - year: "2016"
    value: 0.07
    category: "TII Tadžikistan-SR"
  - year: "2017"
    value: 0.01
    category: "TII Tadžikistan-SR"

  - year: "2008"
    value: 0.02
    category: "TII Turkménsko-SR"
  - year: "2009"
    value: 0.00
    category: "TII Turkménsko-SR"
  - year: "2010"
    value: 0.00
    category: "TII Turkménsko-SR"
  - year: "2011"
    value: 0.00
    category: "TII Turkménsko-SR"
  - year: "2012"
    value: 0.02
    category: "TII Turkménsko-SR"
  - year: "2013"
    value: 0.00
    category: "TII Turkménsko-SR"
  - year: "2014"
    value: 0.00
    category: "TII Turkménsko-SR"
  - year: "2015"
    value: 0.00
    category: "TII Turkménsko-SR"
  - year: "2016"
    value: 0.00
    category: "TII Turkménsko-SR"
  - year: "2017"
    value: 0.00
    category: "TII Turkménsko-SR"
options:
  xField: "year"
  yField: "value"
  seriesField: "category"
  color:
    - "#3b62b0"
    - "#e07834"
    - "#9c9c9c"
    - "#f0bd24"
    - "#569bd5"
  smooth: false
  point:
    size: 3
    shape: "circle"
  yAxis:
    min: 0
    max: 0.45
    tickInterval: 0.05
```

### Vývoj obchodnej intenzity medzi EU a strednou Áziou na základe indexu TII (*2008 - 2018*)
```chartsview
type: Line
data:
  - year: "2008"
    value: 0.34
    category: "TII EU-CA"
  - year: "2009"
    value: 0.41
    category: "TII EU-CA"
  - year: "2010"
    value: 0.43
    category: "TII EU-CA"
  - year: "2011"
    value: 0.42
    category: "TII EU-CA"
  - year: "2012"
    value: 0.42
    category: "TII EU-CA"
  - year: "2013"
    value: 0.40
    category: "TII EU-CA"
  - year: "2014"
    value: 0.41
    category: "TII EU-CA"
  - year: "2015"
    value: 0.50
    category: "TII EU-CA"
  - year: "2016"
    value: 0.50
    category: "TII EU-CA"
  - year: "2017"
    value: 0.45
    category: "TII EU-CA"
  - year: "2018"
    value: 0.44
    category: "TII EU-CA"

  - year: "2008"
    value: 0.55
    category: "TII CA-EU"
  - year: "2009"
    value: 0.50
    category: "TII CA-EU"
  - year: "2010"
    value: 0.60
    category: "TII CA-EU"
  - year: "2011"
    value: 0.58
    category: "TII CA-EU"
  - year: "2012"
    value: 0.64
    category: "TII CA-EU"
  - year: "2013"
    value: 0.67
    category: "TII CA-EU"
  - year: "2014"
    value: 0.69
    category: "TII CA-EU"
  - year: "2015"
    value: 0.75
    category: "TII CA-EU"
  - year: "2016"
    value: 0.73
    category: "TII CA-EU"
  - year: "2017"
    value: 0.79
    category: "TII CA-EU"
  - year: "2018"
    value: 0.78
    category: "TII CA-EU"
options:
  xField: "year"
  yField: "value"
  seriesField: "category"
  color:
    - "#3b62b0"
    - "#e07834"
  smooth: false
  point:
    size: 3
    shape: "circle"
  yAxis:
    min: 0
    max: 0.90
    tickInterval: 0.10
```

### Vývoj indexu obchodnej intenzity medzi EU a EAEU (*2011 - 2020*)
```chartsview
type: Line
data:
  - year: "2011"
    value: 1.38
    category: "EU"
  - year: "2012"
    value: 1.45
    category: "EU"
  - year: "2013"
    value: 1.46
    category: "EU"
  - year: "2014"
    value: 1.37
    category: "EU"
  - year: "2015"
    value: 1.27
    category: "EU"
  - year: "2016"
    value: 1.21
    category: "EU"
  - year: "2017"
    value: 1.19
    category: "EU"
  - year: "2018"
    value: 1.18
    category: "EU"
  - year: "2019"
    value: 1.14
    category: "EU"
  - year: "2020"
    value: 1.11
    category: "EU"

  - year: "2011"
    value: 1.16
    category: "EAEU"
  - year: "2012"
    value: 1.43
    category: "EAEU"
  - year: "2013"
    value: 1.60
    category: "EAEU"
  - year: "2014"
    value: 1.61
    category: "EAEU"
  - year: "2015"
    value: 1.90
    category: "EAEU"
  - year: "2016"
    value: 1.58
    category: "EAEU"
  - year: "2017"
    value: 1.09
    category: "EAEU"
  - year: "2018"
    value: 1.11
    category: "EAEU"
  - year: "2019"
    value: 1.33
    category: "EAEU"
  - year: "2020"
    value: 1.53
    category: "EAEU"
options:
  xField: "year"
  yField: "value"
  seriesField: "category"
  color:
    - "#8b1e3f"
    - "#5a7d9a"
  smooth: true
  point:
    size: 3
    shape: "circle"
  yAxis:
    min: 0
    max: 2.0
    tickInterval: 0.2

```

## Index obchodnej komplementarity (*TCI*)
$$
c^{ij} = 100 \left[ 1 - \sum_{k=1}^{m} \frac{|m_k^i - x_k^j|}{2} \right]
$$

- Do akej miery sa celkový vývoz 1 krajiny prekrýva s tym, co dovážajú ine krajiny
- Dôležité pri hodnotení potencionálnych bilaterálnych alebo regionálnych dohôd

$c^{ij} = 100$ krajiny sú ideálni obchodní partneri
$c^{ij} = 0$ krajiny sú ideálni obchodní konkurenti

- Vysoké hodnoty - obe krajiny môžu z daného obchodu profitovať
- Podmienka - skúmané krajiny by nemali byt geograficky vzdialené

## Index podobnosti
- **SI = Similarity index** - hodnotí podobnosť krajín, respektíve jednotlivých regiónov na základe ich GDP alebo GRDP

$$
SI^{ij} = 1 - \left[\frac{\text{GDP}^i}{\text{GDP}^i + \text{GDP}^j}\right]^2 - \left[\frac{\text{GDP}^j}{\text{GDP}^i + \text{GDP}^j}\right]^2
$$

* $\text{GDP}^i$ – hrubý domáci produkt krajiny $i$
* $\text{GDP}^j$ – hrubý domáci produkt krajiny $j$

- Výsledkom je interval hodnôt **od 0 po 0.5**
- Ak sa hodnota indexu **približuje k 0**, ide o rozdielne krajiny/regióny
- Čím viac sa hodnota **priblíži k 0.5**, tým väčšia je podobnosť daných krajín (*regionov*)
- Krajiny s **podobnou veľkosťou ekonomiky** sa podieľajú aj **na väčšom** vzájomnom **obchodovaní**

# Viacfaktorové indikátory hodnoteia
Zložité indexy zavedené medzinárodnými organizáciami, ktoré vytvoril komplexnú metodiku pre zber, kvantifikáciu, spracovanie a porovnanie jednotlivých aspektov medzi krajinami na globálnej úrovni.

- Index globálnej konkurencieschopnosti (*GCI*)
- Celosvetový index konkurencieschopnosti (*WCI*)
- Index znalostnej ekonomiky (*KEI*)
- Index ekonomickej slobody (*IEF*)
- Index inštitucionálnej kvality (*WGI*)
- Index vnímania korupcie (*CPI*)

# Ekonometrické modely
Regresné a korelačné analýzy a pod., Gravitačný model

# Kvalitatívne indikátory
SWOT analýza, prieskum formou dotazníkov, riadene a štrukturované rozhovory, ďalšie kvalitatívne metódy