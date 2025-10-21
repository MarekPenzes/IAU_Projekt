# IAU_Projekt

Marek Penzeš & Samuel Petrík

Projekt na predmet IAU - skúmanie a úprava dát v rámci datasetov

# THE QUEST
Každá dvojica bude pracovať s pridelenou dátovou sadou od 2. týždňa. Vašou úlohou je predikovať závislé hodnoty premennej “oximetry” (predikovaná premenna) pomocou metód strojového učenia. Budete sa musieť pritom vysporiadať s viacerými problémami, ktoré sa v dátach nachádzajú ako formáty dát, chýbajúce, vychýlené hodnoty a mnohé ďalšie. 

Očakavaným výstupom projektu je:
  1. najlepší model strojového učenia;
  2. data pipeline pre jeho vybudovanie na základe vstupných dát.

# 1. Fáza projektu
# 1.1 Základný opis dát spolu s ich charakteristikami
  A Analýza štruktúr dát ako súbory (štruktúry a vzťahy, počet, typy, …), záznamy (štruktúry, počet záznamov, počet atribútov, typy, …) <br/>
  B Analýza jednotlivých atribútov: pre zvolené významné atribúty (min 10) analyzujte ich distribúcie a základné deskriptívne štatistiky a či spĺňa predpísané podmienky a rozsah meraných hodnôt. <br/>
  C Párová analýza dát: Identifikujte vzťahy a závislostí medzi dvojicami atribútov. <br/>
  D Párová analýza dát: Identifikujte závislosti medzi predikovanou premennou a ostatnými premennými (potenciálnymi prediktormi). <br/>
  E Dokumentujte Vaše prvotné zamyslenie k riešeniu zadania projektu, napr. sú niektoré atribúty medzi sebou závislé? od ktorých atribútov závisí predikovaná premenná? či je potrebné kombinovať záznamy z viacerých súborov? <br/>
# 1.2 Identifikácia problémov, integrácia a čistenie dát
  A Identifikujte aj prvotne riešte problémy v dátach napr.: nevhodná štruktúra dát, duplicitné záznamy, ktoré môžu vznikať po určitých dátových transformáciach, nejednotné formáty, chýbajúce hodnoty, vychýlené hodnoty. V dátach sa môžu nachádzať aj iné, tu nevymenované problémy, resp. menej problémov ako bolo uvedených. <br/>
  B Kontrola správnosť v dátach: <br/>
    B1 či obsahujú abnormálne hodnoty <br/>
    B2 či obsahujú nelogické dátové vzťahy, ktoré sú následkom dátovej kolekcie a anotovania dát   <br/>
  C Vychýlené hodnoty (outlier detection), vyskúšajte riešiť problém min. 2 technikami <br/>
    C1 odstránenie vychýlených alebo odľahlých pozorovaní <br/>
    C2 nahradenie vychýlenej hodnoty hraničnými hodnotami rozdelenia (napr. 5%, 95%) <br/>
# 1.3 Formulácia a štatistické overenie hypotéz o dátach
  A Sformulujte dve hypotézy o dátach v kontexte zadanej predikčnej úlohy. Formulované hypotézy overte vhodne zvolenými štatistickými testami. <br/>
  B Overte či Vaše štatistické testy majú dostatok podpory z dát, teda či majú dostatočne silnú štatistickú silu. <br/>

