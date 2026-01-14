# Rtg záření
- paprsky x
- elmag vlny
- $\lambda$ = 0.4 - 2.5 Angstrom
- nedá se fokusovat
- první analyzovaná struktura: NaCl
- index lomu = 0.99995 - souvisí nějak s grupovou a fázovou rychlostí
    - rád se totálně odráží - na více vrstvách má braggovské peaky
    - montel optika
# Difrakce 
1) kinematická
    - difrakce je interference rozptýleného záření
    - zanedbáme vícenásobnou interferenci
    - dobrá aproximace pro nedokonalé krystaly
2) dynamická
   - difrakce zároveň s absorpcí
   - difrakce je řešením maxwellek
   - uvažujeme vícenásobnou interferenci
   - dobrý popis pro dokonalé krystaly
- Thompsonův rozptyl - bez změny energie fotonu, jen změna směru
- Comptonův rozptyl - změna energie fotonu
- absorpce - zvýší se teplota
- fotoelektrický jev - vyráží to elektrony: rtg. fluorescence
- kinematická absorpce: $I = I_0 \exp(-\mu d)$

### Thompsonův rozptyl
- kmitající elektron vyzařuje jako dipólová anténa
- Pro volné elektrony: výraz pro elektrické pole je úměrný 1/m -> vidí to převážně elektrony
  <img width="1001" height="579" alt="image" src="https://github.com/user-attachments/assets/bbfb2a30-1857-4365-ae9c-df2a915940b9" />

- Vázané elektrony: pohybová rovnice tlumeného LHO
<img width="983" height="626" alt="image" src="https://github.com/user-attachments/assets/958db757-472d-42b4-bda1-b6a8b2430972" />

  
- Pro vázané elektrony pole závisí na vlastní frekvenci
- po interakci dostanu fázový posun - $-\pi$ pro Thompsona, 0 pro Coptona
- metoda anomálního rozptylu - dostanu jiné obrazy pro různé vlnové délky -> dostanu jiné obrazy -> vím která vlastní frekvence to způsoila -> mám navíc informaci o prvku
<img width="922" height="704" alt="image" src="https://github.com/user-attachments/assets/d04b8d2a-9817-48a3-9acc-19764d30aa32" />

- Nepolarizované záření se difrakcí částečně polarizuje (ale tyjo netuším co je to theta) - tohle platí jen pro nepolarizované
- <img width="951" height="301" alt="image" src="https://github.com/user-attachments/assets/59749516-8253-417a-b0d9-2b3b5d828c4c" />
- bacha $I = |E|^2$
- difrakce rtg. na neutornech se neděje
- rtg na elektronech je by far dominantní
**Pro dva elektrony je to asi upočitatelné**
  - difrakčí vektor: $Q = (4\pi/\lambda) \sin \Theta$
    <img width="1288" height="768" alt="image" src="https://github.com/user-attachments/assets/8b72eee7-2963-479a-8e58-28b0c2afd0f5" />

- Mohu z toho určit strukturu
- rtg. je vůči stavům rychlé -> potřebuju to středovat až přes N částic
- středování vyhladí oscilace
- Sumu si nakonec nahradím integrálem přes objem té elektronové hustoty
- *vlastně*: je to fourierova transformace elektronové hustoty, záleží na tom kde a kolik je elektronu -> fázový posuv -> sčítám jen světl s dobrým fázovým posuvem
- nakonec aproximuju atom koulí...úměrné $\sin(Qr)/(Qr)
  **Atomový rozptylový faktor je fourierkou elektronové hustoty - tohle bysme si měli pamatovat když už ne ty detaily**
  - celkem je to součet příspěvků od jednotlivých elektronů - pro s je to široké, pro ostatní (méně lokalizované) je to užší
    <img width="386" height="703" alt="image" src="https://github.com/user-attachments/assets/e5ac8c53-647b-40f7-8616-23ed69987033" />

na ose x je vektor v reciprokém prostoru*
  - Standartně používáme jednodušší formulku - tohle stačí vždycky:
    <img width="817" height="131" alt="image" src="https://github.com/user-attachments/assets/5dd390fa-f9ae-4d66-aadd-0ab9135f7d11" />

    , kde $a_i$, $b_i$ a $c$ je tabelováno pro každý prvek (ion)

Srovnání elektronů, x-ray a neutronů na elektronech 
- elektrony jsou asi 3x silnější než x-ray (silněji interaguijí)
- neutrony nevidí nic - rozptylový faktor je konstanta
- tedy je výhodné dělat difrakci pro x-ray a elektrony na malých úhlech -> výsledky jsou silnější protože rozptylový faktor je vyšší
- f(Z) je přímo úměrné pro x-ray a hodně skáče pro neutrony (Z je počet nukleonů) -> kombinací X a neutronů v difrakci rozliším izotopy
- blízko absorpční hrany mi to roste -> musím taylorovat
### Molekuly
- složitější - musím například uvažovat podél které osy to dělám
- příklad: CF$_4$
<img width="415" height="379" alt="image" src="https://github.com/user-attachments/assets/a5e1e8c0-6f0b-41de-a6e1-fe7c335f08dc" />

Maxima ve faktoru pro molekulu odpovídají meziatomovým vzdálenostem:
<img width="1388" height="776" alt="image" src="https://github.com/user-attachments/assets/3fa1c3d2-143f-4615-a7f9-bf8bccd199f2" />

*Pro molybden tam maxima nejsou LOL*

Amplituda v dirfakci je pak dána atomovým rozptylovým faktorem
<img width="1388" height="776" alt="image" src="https://github.com/user-attachments/assets/fd816bdc-399e-4cd7-ad20-4d204756f0a4" />

To úplně dole je Debayova formule - mám to z prvních principů - pro tísíce to jde, pro 1 mol...asi těžko

Pro pravidelné struktury stačí spočítat buňku

**Pro řetízek:**
- intenzita roste s N$^2$
- nakonec dostanem 3D krystal
<img width="1388" height="776" alt="image" src="https://github.com/user-attachments/assets/f2e331c0-09b1-40a2-a6d5-eb5e5761823a" />

*Nakonec z toho dostanem vyhasínací podmínky*

V reciprokém prostoru platí
  1) fcc -> bcc
  2) bcc -> fcc

<img width="553" height="622" alt="image" src="https://github.com/user-attachments/assets/6e8cd8d4-0faf-43c7-91fb-eaa8a3d237ab" />

### Tohle je dpč nutné vědět
<img width="804" height="173" alt="image" src="https://github.com/user-attachments/assets/6884c9ee-9001-4b1f-82a0-9dd9a389dbae" />

Nebo tak to alespoň vypadá z té přednášky


Když mám kratší mezorvinné vzdálenosti tak mi ten strukturní faktor jde dolů (kraj atomu je skoro v protifázi se středem)


Fázový problém -> ztrácíme informaci o fázi - u centrosymetrických nevíme "jen" znaménko
- příklady: počítání pro jednotlivé struktury
- **bacha** beru vždy jen ten jeden atom co tam řádně náleží (u primitivní si ho dám třeba do počátku LOL a znuuje se mi ten hnusnej faktor)
- vyhasínací podmínky:
    - bcc sežere lichý součet h+k+l, pro sudé dostanu něco
    - fcc sežere smíšené hkl. Pro všechny sudé nebo liché dostanu něco.
    - pro NaCl je to složitější - liché jsou potlačené
    - šroubové osy vyhasínají kvůli ekvivalentním polohám (dosadím ekvivalentní polohy a občas dostanu 0)
  
Šířka difrakčních maxim:
- sherrerova rovnice
- čím menší krystal, tím širší linie
- 2w = $0.94\lambda / (D*\cos \Theta)
- dynamické výchylky - třeba při defektech
  <img width="1341" height="508" alt="image" src="https://github.com/user-attachments/assets/d63abfc6-ac46-41aa-9091-f4a9c57a8a39" />

- chci zas střední hodnotu, protože difrakce je okamžitá
- Debayeův-Wallerův faktor - teplotní faktor, kakonec mi vyjde prostě exponenciální rozptyl
- přidá se faktor co snižuje intenzitu a rozšiřuje peak -> difrakce na teplých krystalech je na hovno
- rozšíření odpovídá fononům -> studium fononových spekter (přešlo se k neutronům, ale dneska se to zas dělá na synchrotronech)
- 
  <img width="743" height="833" alt="image" src="https://github.com/user-attachments/assets/d3c28979-6a5c-40e3-ad59-5eed87dbcbe4" />

*very nois photo UwU, Kužel je dojat   * <img width="74" height="107" alt="image" src="https://github.com/user-attachments/assets/eabb9f74-402b-4a0a-8931-39f6f42a488b" />

- Debayeova teplota - ono to není přesně, tak závisí na teplotě
    - kužel to dostal na diplomku
    - Debayeův faktor:
 
      <img width="698" height="124" alt="image" src="https://github.com/user-attachments/assets/c0259a3b-89d2-43b1-9476-19d8b4335c18" />

      Když to zlogaritmuju, dostanu Wilsonův graf:

      <img width="1116" height="770" alt="image" src="https://github.com/user-attachments/assets/da55e00c-1c11-475d-93ce-121199f97ba0" />


- Ze směrnice mám střední kvadratickou výchylku
- teplotní kmity jsou elipsa

**Důležité**

Jak vypadá strukturní faktor
rozdíl elektroy neutrony
co je atomový faktor a nějaké ty grafíky

- my ten rozptyl ale nezjistíme, zjistíme jen intenzitu (kvadrát)
- **Fridelův zákon** - intenzita je stejná i když rovinu otočím o 180˚
  - anomální difrakce se ale chová jinak pro necentrosymetrický krystal
- Laueova grupa symetrie - jen 11
- existuje Pattersonova funkce - polže mi alespoń s meziatomovými vzdáenostmi
- dneska: chemicky nahradím nějaký atom těžším atomem -> anomální disperze (na synchrotronu) -> vím který atom způsobuje tu anomálii a mám alespoň nějakou informaci



