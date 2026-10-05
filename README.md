## R&D Roadmapa projektu

Všechny podrobnosti a prameny dokumentace zde na [WIKI](https://github.com/Stekra88/Jumping-Hexapod/wiki). &gt; 

**Stav projektu:** $${\color{orange}Fáze\space0 – Zahájení \space projektu / Rešerše \space a \space teoretický \space koncept}$$

### Fáze 1: Rešerše, koncept a dimenzování *(Právě probíhá)*
- [ ] **Rešerše robotů:** 4-nohé roboty, hexapody, stavba nohy, její kinematická struktura, využití lankového převodu.
- [ ] **Rešerše pohonů:** Analýza kvazipřímých pohonů (QDD), lankového převodu (Capstan drive) a ostatních druhů převodů.
- [ ] **Geometrie končetiny:** Stanovení hmotnostního modelu.
- [ ] **Teoretické výpočty:** Stanovení potřebného krouticího momentu, otáček a výkonu aktuátoru pro potřebné zrychlení při odrazu a dopadu.

### Fáze 2: Simulační prostředí & Matematický model (MuJoCo)
- [ ] **Základní model v MuJoCo:** Vytvoření 1D modelu jedné nohy / zkušebního rigu pro pár protilehlých nohou na svislém vedení.
- [ ] **Základní řízení:** Polohování, řízení modelu 
- [ ] **Řízení dopadu (Dampening):** Návrh impedančního řízení v ose Z.

### Fáze 3: Návrh hardwaru & Výroba 1. demonstrátoru
- [ ] **Výběr komponent:** Specifikace brushless motoru a řídicí jednotky s podporou CAN-FD.
- [ ] **Konstrukce v CAD:** Návrh lankového převodu a prostorově úspornou sektorovou kladkou.
- [ ] **Stavba kloubu:** Výroba a sestavení jednoho fyzického kloubu (3D tisk / hliníkové díly, uhlíkové trubičky).

### Fáze 4: Testování 1D kloubu & Navazující bakalářská práce
- [ ] **Ověření funkce kloubu:** Fyzické otestování řízení polohy a demonstrace zpětné poddajnosti.
- [ ] **Pádový test:** Jednoduchá fyzická zkouška absorpce nárazu na jednom kloubu. Na obou kloubech.
- [ ] **Stavba 1D dvousetového rigu:** Realizace zkušebního standu pro pár nohou (resp. jednu nohu) a porovnání naměřených dat se simulací v MuJoCo.
---
