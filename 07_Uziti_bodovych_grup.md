# Tvar a určení třídy 
**forma** - systém cymetricky ekvivalentních rovin (ve {})
  - pokud jedna z rovin je vnější plocha i zbytek rovin formy bude vnější forma
### Jednoduché formy
- mám jen dvojčetnou osu
    - pinakoid - dvě rovnoběžné roviny - jen na spojkách s jinými tvary
    - diedr - roviny jsou nakoloněné
    - monoedr - rovina je kolmo k ose
- obecné formy - obecné polohy
- speciální - tvary jsou jednodušší protože to má menší četnost
- tvary nebude zkoušet ale základní tvary bychom mohli vědět
- často jsou platónská tělesa
- asi je dobré umět cirka nakreslit stereografickou projekci krychle
- musím mít symetrii ale ty tvary můžou vypadat úplně jinak

<img width="471" height="531" alt="image" src="https://github.com/user-attachments/assets/5cf9dc4b-e605-4e7c-b32d-34746170dae6" />

*tohle jsou ty základní tvary* - asi není potřeba umět všechno, ale jen nějaký základ

- pyramidy
- dipyramidy
- trapezoedry - má to cik cak rovník
- sklenoedr - jinak cik cak rovník
 
  <img width="685" height="509" alt="image" src="https://github.com/user-attachments/assets/c3440869-66e9-4a9d-bcb5-cc33aebb4961" />

<img width="685" height="509" alt="image" src="https://github.com/user-attachments/assets/e1b18101-8fdb-47e3-8c78-a6afbb61bab2" />

Prý to nebude doslova zkoušet ale asi je dobrý tušit jak to vypadá

- Určovat symetrie je zrádné - pyrit není úplně krychle - je to čtverečné
- holosymetrické - stejná symetrie jako mřížové body
- merosymetrie - jiná symetrie - asi že v křemenu je šestičetná osa ale reálně jen 3četná
- enantiomery - liší se levá a pravá
### Metody určení
- kouknu a vidím
- naleptám, kouknu na díru a kouknu na tvar díry - jsou velké atlasy ale ani kužel to neviděl v praxi
- Některé plochy při růstu zanikají (z šestiúhelníku je postupně čtverec)
- optické vlastnosti
  - enanitomery stáčí rovinu polarizovaného světla
  -  piezoelektrický jev pouze bez středu symetrie a os 4,3,2
  -  *Jednoosé krystaly:* tetragonální, hexagonální, trigonální
  -  *Dvojosé:* trikliniciké, monoklinické, ortorombické
  -  *Izotropní:* kubické
  -  pokud ten jev nepozoruju, tak nemohu dělat závěry
### Zákony gemetrické krystalografie
- to jsou ty věty ze začátku
- říká to třeba že všechny osy mají jeden průsečík
## Tenzorový popis veličin 
- *skaláry* - hmotnost, objem
- *vektory* - elektricá intenzita, pyroelektrický jev
- *tenzory* - deformace, vodivost
- $B = T * A$, B má řád p, A má řád q, T má řád p+q
- pokud nemám symetrie, potřebuju 81 nezávislých složek
- po obložení mohu ddostat kvadriky - dostanu hezké grafické znázornění

  <img width="683" height="456" alt="image" src="https://github.com/user-attachments/assets/029bc9e3-1004-47ba-9340-c6a929360350" />

Hodnota veličiny T ve směru q:
1) $c_k = \cos (q*x_k)$, kde $x_k$ jsou vektory podél elementární mříže
2) udělám vektor c ze směrových kosinů
3) vynásobím to s tenzorem: t = c*T*c
- i chemicky identitcké látky se stejnou soustavou můžou mít jiné tenzory
  - ve zkratce: je to bordel
**Neumannův princip** - symetrie fyzikální vlastnosti nemůže být nižší než je symetrie dána bodovou grupou. (NE naopak)
  - *formálně:* grupa $G_T$ operací symetrie fyzkální vlastnosti T krystalu musí obsahovat všechny operace symetrie bodové grupy K tohoto
  - krystalu. Grupa K je tedy podgrupou grupy $G_T$, $K \in G_T$.
 
**Voigotův princip** - tenzor fyzikální vlastnosti se nesmí měnit při žádné operaci symetrie krystalové grupy K

**Curiův princip** - krystal pod vlivem vnějšího působení změní symetrii tak, že zachová pouze prvky společné se symetrií vnějšího působení.

**Bude chtít minimální operace symetrie v soustavách**

- bodové grupy nejsou rovnoměrně zastoupeny
  - 44% organických a 34% anorganických látek má 2/m
  - 94% organických látek je triklinických, monoklinických nebo orthorombických
  - symetrických látek je prostě málo
  - $\bar{6}$ je extrémě nezastoupená
  - 95% látek může být dvojlomných
# Polykrystalické materiály (kapaliny)
- curiovy grupy
- mají nekonečněčetnou osu (váce, kužely, kruhy, koule)
- je jich jen 7
- u hematických krystalů třeba může být uspořádání -> dvojčetné osy a tak
### Pyroelektřina
- změna polarizace při změně teploty
- ne v centrosymetrických materiálech - průser prostě je že to je popsáno vektorem no. to tam pak vyjde p = -p a jsem v háji
- $P_i = p_i \delta T$
- dvojčetná osa taky bude problém,
- To že to grupa umožňuje neznamená, že to v tom krystalu bude
### Dielektrické konstanty
- permitiita
- $D_i = \varepsilon_{ij} E_j$
- zachování energie -> symetrický tenzor
  - uložená energie nezávisí na pořadí derivací
- definitně pozitivní - zase z nějaké fyziky
- Voigot: když to obložím maticemi symetrie, dostanu původní matici
- *Kubické* - jeden nezávislý element, který je třikrát na diagonále
- *Triklinické* - potřebuju všech 9 elementů
- mohu měřit závisost jednotlivýc složek na teplotě
### Napětí a deformace
- Potřebuju fakt velkej tenzor (4 dimenze)
- Změna objemu je součet diagonálních členů
### Teplotní roztažnost
- Symetrický tenzor 2. řádu
- nemusí být pozitivně definitní
### Piezoelektřina
- zas tenzor 3. řádu asi
- pro sacharózu mám 8 nezávislých složek a dá se to tam naměřit
- i dřevo má piezoelektřinu - grupa 222
### Elasticita 
- tenzor 4. řádu
- až 81 složek
- pro *kubické* ale stačí 3 konstanty
- Tu už můžeme mít velkou anizotropii - grafit
- jsou teplotně závislé a to dost nepředvídatelně
### Stlačitelnost
- dobrá závisost na délce vazby
  - delší vzby jsou stlačitelnější
