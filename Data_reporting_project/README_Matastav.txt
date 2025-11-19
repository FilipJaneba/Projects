
README – Odovzdané podklady pro Matastav

1. Mockupy (screenshots/fotky):
Vytvorené v nástroji draw.io. Zobrazujú návrh Power BI dashboardov rozdelených do 3 tematických oblastí:
- Zákazníci – skupiny, hodnotenie, objednávky
- Mzdy – vývoj miezd, zamestnanci, prémiová zložka
- Cashflow – plánované vs. skutočné príjmy/výdaje, faktúry, rozpady

Priložené súbory:
- Zakaznici - mockup.png
- Mzdy - mockup.png
- Cashflow - mockup.png

2. Hrubá dimenzionálna analýza – Excel:
Súbor Analyza_dimenze_ukazatele – návrh.xlsx obsahuje návrh dimenzionálneho modelu s identifikáciou:
- Dimenzí (napr. zákazník, zamestnanec, pobočka...)
- Faktových tabuliek a ukazateľov
- Vzťahov medzi tabuľkami a návrh merateľných metrík

3. Datový model DWH vrstvy L1 – screenshot:
Vizualizácia vytvorená v Lucidchart obsahuje:
- Dimenzie: D_zakaznici, D_zamestnanci, D_pobocky, D_cas, D_zdroje, D_druh_vydaje, D_stav_faktury
- Fakty: F_Kontrakty, F_Faktury, F_Penezni_tok
- Vzťahy medzi tabuľkami cez kľúče

Priložený súbor: datovy_model_lucidchart.png
Online verzia: Lucidchart link vo Worde

4. SQL skripty pre L1 transformácie v BigQuery:
Súbor SQL scripty.docx obsahuje transformácie dát z L0 do L1

Poznámka: Skripty pravdepodobne nie sú finálne – po zmenách neboli exportované, môže sa líšiť aktuálna verzia v systéme.

5. Power BI (pbix) report:
V power BI sme vykonali odstránenie duplicít u faktúr pomocou power query
Posielame Power BI súbor (.pbix) s reportami.
Dáta sú v Import móde, report pokrýva sledovanie problémových oblastí, zákazníkov, zamestnancov a pobočiek.

6. Prezentácia pre management Matastavu:
Posielame finálnu prezentáciu (.pptx) so zhrnutím výskumu, výsledkami a odporúčaniami.
