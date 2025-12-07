---
{"dg-publish":true,"permalink":"/01-school/matematika-a-statistika/statistika-regresna-analyza/","tags":["year2","winterSemester","uniVKzMaS"]}
---

# Transkripcia dát (12 pozorovaní)
- y (cena v tis. €): 67, 94, 79, 96, 115, 105, 107, 126, 113, 125, 148, 127
- x (úžitková plocha v m²): 40, 48, 53, 61, 64, 70, 74, 78, 83, 89, 92, 100

Odtiaľ:
- n=12

$$
\bar y = 1302/12 = 108{,}5
\bar x = 852/12 = 71
$$
  
# Odhad lineárneho regresného modelu (úloha a)
Použijeme štandardné vzorce

$$
\hat\beta_1 = \frac{\sum (x_i-\bar x)(y_i-\bar y)}{\sum (x_i-\bar x)^2},\qquad \hat\beta_0 = \bar y - \hat\beta_1\bar x.
$$

Zo súčtov (alebo priamo z dát) dostaneme:

  
$$
\sum (x_i-\bar x)(y_i-\bar y) \approx 4069
$$

$$
\sum (x_i-\bar x)^2 = 3772
$$

Po dosadení:

$$
\hat\beta_1 \approx \frac{4069}{3772} \approx 1{,}07874, \qquad \hat\beta_0 \approx 108{,}5 - 1{,}07874\cdot 71 \approx 31{,}91.
$$

Teda odhadovaný regresný model (cena v tis. €):

$$
\hat y = 31{,}91 + 1{,}0787\,x.
$$
  
Interpretácia koeficientov: priemerne každé +1 m² úžitkovej plochy zvyšuje cenu o približne 1,079 tis. € = ~1 079 €. Intercept ≈ 31,91 tis. € je teoretická predpoveď pre x=0 (nemá praktický zmysel, len matematický).

# Intenzita vzťahu a časť variability vysvetlená modelom (úloha b)

Počíta sa koeficient determinácie R^2 (alebo korelačný koeficient r).

Z dát:

$$
\sum (y_i-\bar y)^2 = 5517
$$

korelácia r =

$$
\dfrac{\sum (x_i-\bar x)(y_i-\bar y)}{\sqrt{\sum (x_i-\bar x)^2\sum (y_i-\bar y)^2}} \approx 0{,}892
R^2 = r^2 \approx 0{,}7956 \approx 79{,}6\%.
$$

Ďalší pohľad: SSR (vysvetlená variabilita) ≈ 4389, SST (celková variabilita) = 5517, SSE (nevysvetlená) ≈ 1127.

Interpretácia:

$$
r\approx 0{,}892
$$
znamená silnú kladnú lineárnu závislosť medzi plochou a cenou.

$$
R^2\approx 0{,}796
$$
Znamená, že približne 79,6 % variability cien bytov v tejto vzorke je vysvetlených lineárnym vzťahom s úžitkovou plochou; zvyšných ~20,4 % je spôsobených inými faktormi alebo náhodou.

Poznámka o malom rozdiele v poslednom čísle