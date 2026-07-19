# Kreatininszint longitudinális változása CKD státusz szerint 2-es típusú cukorbetegekben

**Lajos Háló, PharmD**

*Portfólióprojekt a RobotDreams Biomedikai adatelemző kurzus keretében.*

**Kulcsszavak:** R • Biostatisztika • Lineáris Mixed Effects Modellek •
Longitudinális elemzés • Klinikai adatelemzés

------------------------------------------------------------------------

## Projekt áttekintése

Ez a projekt egy 2669 magyarországi 2-es típusú cukorbeteg (T2DM)
adatain alapuló longitudinális elemzést mutat be. A vizsgálat célja
annak meghatározása volt, hogy a krónikus vesebetegség (CKD) státusza
összefügg-e a szérum kreatininszint időbeli alakulásával a
glikémiacsökkentő kezelés megkezdését követő 12 hónap során.

A hiányzó adatokat a **missForest** algoritmussal imputáltam, majd a
longitudinális elemzést **lineáris mixed effects (LME)** modellel
végeztem.

## Kutatási kérdés

Különbözik-e a kreatininszint változásának mértéke a glikémiacsökkentő
kezelés megkezdését követő 12 hónapos követési időszakban CKD-pozitív és
CKD-negatív T2DM-betegek között az életkor, nem, BMI, hipertónia és
kezelési csoport figyelembevételével?

## Főbb eredmények

-   2669 beteg adatain végzett longitudinális elemzés.
-   missForest imputáció.
-   Lineáris mixed effects modell alkalmazása.
-   Szignifikáns CKD × idő interakció (β = +0,41 µmol/L/hónap; p =
    0,002).
-   A log-transzformált érzékenységvizsgálatban az interakció nem maradt
    szignifikáns.

## Alkalmazott R csomagok

-   tidyverse
-   missForest
-   tableone
-   lme4
-   lmerTest
-   emmeans
-   performance
-   ggplot2

## Megjegyzés

Ez a projekt oktatási és portfólió célból készült. Nem szolgál klinikai
döntéshozatal támogatására.

------------------------------------------------------------------------

*RobotDreams -- Biomedikai adatelemző kurzus • 2026*
