# Projekt HADR: Research and Development Documentation



Tento dokument slouží jako záznam výzkumu a vývoje (R&D) pro návrh dynamického systému skákajícího hexapoda. Zaměřujeme se na teoretický návrh a následnou validaci tří fází pohybu: dopad, odraz a let.

## Výzkum mechaniky a aktuátorů

* **Klouby a převody:** Pro osy odrazu (Pitch) teoreticky zkoumáme využití lankového převodu (Capstan drive). Jeho hlavní výhodou pro náš výzkum je absence pasivního tření a vůle, což by mělo poskytnout zpětnou poddajnost nezbytnou pro bezpečné tlumení dopadů. Planetové převodovky zvažujeme nasadit pouze pro osu zatáčení (Yaw), kde nehrozí rázové zničení ozubení.


* **Pohonné jednotky:** V rámci rešerše analyzujeme možnosti kvazipřímých pohonů (QDD). Jako jedna z možností se jeví využití plochých outrunner (tzv. pancake) motorů díky jejich teoreticky vysokému krouticímu momentu. Výběr konkrétního hardwaru nadále podléhá zkoumání.


* **Optimalizace měřítka:** Naše matematické modely naznačují, že zkrácení femuru na 6 až 7 centimetrů výrazně sníží nároky na krouticí moment. Pracovní hypotéza cílí na celkovou hmotnost systému kolem 1,5 kilogramu.



## Metodika vývoje a testování

* **Laterální síly:** Zvolený pavoučí (sprawling) postoj generuje při odrazu a dopadu asymetrické boční síly.


* **Koncept testovacího rigu:** Z výzkumu chování sil vyplývá, že testování jediné končetiny na vertikální ose by vedlo ke vzpříčení vodicích ložisek. Náš návrh testovacího standu proto teoretizuje využití páru protilehlých nohou, kde se horizontální síly vektorově vyruší.



## Simulace a softwarová architektura

* **Simulační prostředí:** Proběhl průzkum dostupných fyzikálních enginů pro dynamickou robotiku. Na základě rešerše bylo zkoumáno prostředí MuJoCo, které s největší pravděpodobností zvolíme jako hlavní nástroj pro simulace díky jeho pokročilému řešení kontaktních sil.


* **Strukturální řízení:** Zkoumáme teoretický návrh softwarového stavového automatu pro detekci kontaktu s podložkou, aby bylo možné v reálném čase přepínat řídicí strategie mezi letem a odpružením na zemi.

