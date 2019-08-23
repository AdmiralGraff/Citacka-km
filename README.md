# Citacka-km

Čítačka počtu km, ujetých k alebo od alebo s Dodem. 

Koncepce: 
    Pouze zvolíme kterou trasou se jelo a automaticky se sečte počet km. 
    At už hornú, dolnú trasu. 
    
Formulár (názov a typ doplnených údajov{input types}):
    - dátum (funkcia "date")
    - čas (funkcia "time")
    - odkiaľ (funkcia výberu zo zoznamu)
    - kam (funkcia výberu zo zoznamu)
    - typ dopravného prostriedku (vlak/bus/auto funkcia "radio")
    - pasažieri (funkcia "radio")
    - dôvod cesty (funkcia "text")
    
JavaScript :
    Tlačítko na select z možnost 
    Nabídka vyberu možnosti 
    Tabulka pro výpis:
    - odkiaľ (funkcia výberu zo zoznamu)
    - kam (funkcia výberu zo zoznamu)
    - dátum
    - čas
    - typ dopravného prostriedku (vlak, auto, autobus)
    - pasažieri (Veverka (V), Dodo (D), Dodo & Veverka (DV)
    - dôvod cesty (funkcia bez výberu možností, slúžiaci len na formát "text", kde bude môcť užívateľ doplniť účel cesty)
    - automatická aktualizácia výpisu
    - možnosť vymazania buď jednej, alebo naraz (označenie použitím "chceckbox") viacerých ciest (napríklad kvôli zlým zadaným údajom)
    !!!POZOR!!! Táto stránka musí byť aj po odídení stránky taká istá ako pred odchodom, t. j. aby užívateľ mohol aktualizovať tú stránku, aby aj po refreshi celej stránky sa nič nezmenilo, aby sa všetky údaje nemusi vyplňovať znovu
    - zoradenie ciest podľa dátumu (na vrchu najnovšia a na spodku najstaršia cesta)
    - súčet na spodku
        - kilometrov spolu
        - kilometre ujetych len Veverkou
        - kilometre ujete len Dodom
        - kilometre všetky spolu (spoločné cesty sa počítajú ako 1 cesta)
        - kilometre všetky všetky spolu (spoločné cesty sa počítajú ako 2 cesty)
        - počet použia jednotlivých typov dopravných prostriedkov)
        - počet koľko ciest spolu bolo

(HTML, :
    Nový rok) 
