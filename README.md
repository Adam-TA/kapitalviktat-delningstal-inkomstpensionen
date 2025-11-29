### Preliminär innehållsförteckning
- [ ] Abstract
- [x] Innehållsförteckning
- [x] Bakgrund, syfte
- [ ] Ordlista
- [ ] Inkomstpension
- [ ] Ekonomisk dödlighet
- [ ] Metod, data
- [ ] Analys, variabler
- [ ] Scenarion
- [ ] Resultat
- [ ] Diskussion
- [ ] Appendix




# To-do
- Klistra in screenshots eller så på pensionsbehållningen som lönesimuleringen peggats mot, samt lägg in formeln för beräkning av fördelningens medel och varians. Tycker spridningen är för stor nu, kan behövas ett intercept för att höja lägstanivån
- Hade sannolikt kunna bli snyggare att göra allt i Notebook, blir en intial kostnad i att lära sig formatera grafer och tabeller men efter det mycket smidigare
- Kanske kan ta en kurs om det på arbetstid, lär dyka upp behov igenom likt med dödligheten...
- Förtydliga denna formel i rapporten: ((1 + avk_ranta - franta)**( df_final['ExpYL'].apply(floor)) - 1) / (avk_ranta - franta) +  
                                        (df_final['ExpYL'] - df_final['ExpYL'].apply(floor))*(1 + avk_ranta - franta)**df_final['ExpYL']
- Se över lönerna, inte rimligt att kvinnorna skiljer så mycket?


# Kapitalviktat delningstal i inkomstpensionen

Repot innehåller analys, kod och underlag som används i projektet om **kapitalviktat delningstal i inkomstpensionen**. Repo:t kompletterar en separat rapport (PDF) och innehåller all nödvändig data och beräkningskod för att replikera resultaten.

## Innehåll

Repo:t består av följande huvuddelar:

  - Rapport som beskriver metod, teori, resultat och slutsatser
  - Jupyter-notebook med beräkningar, simuleringar, grafer och steg-för-steg-implementering av kapitalviktat delningstal och ekonomisk dödlighet
  - Grunddata för dödlighet, lönesimuleringar
  - Figurer och tabeller

---

## Syfte

Projektet undersöker:

- Hur individeras erhållna andel av sin intjänade pensionsbehållning korrelerar med behållningens storlek
- Den genomsnittliga avvikelsen mellan erhållen andel och prognosticierad erhållen andel
- hur ett **kapitalviktat delningstal** kan konstrueras
- det kapitalviktade delningstalets skillnader mot nuvarande metod för delningstal


