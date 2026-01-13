## Operace symetrie
1) zrcadlení <img width="290" height="285" alt="image" src="https://github.com/user-attachments/assets/0a8ad785-db74-4326-ac56-0a2cd12963a1" />
2) Translace <img width="297" height="291" alt="image" src="https://github.com/user-attachments/assets/eac84d8f-e7d9-41a8-b676-c331a50f3c12" />
3) Rotace <img width="322" height="318" alt="image" src="https://github.com/user-attachments/assets/0e194515-7b05-4999-a26f-d5e5014c2e5c" />
4) Skluz a rotace <img width="342" height="312" alt="image" src="https://github.com/user-attachments/assets/34adea61-d596-4d8e-ba03-8d9d8f359078" />
Izometrie - posunutí co zachová vzdálenosti
bodové operace - zachovají jeden pevný bod
Operace symetrie - po operaci je objekt nerozlišitelný od originálu

Osy rotace značím n-úhelníky

S translační periodicitou jsou slučitelné jen některé rotace - 1.2.3.4.6
<img width="618" height="243" alt="image" src="https://github.com/user-attachments/assets/df1f219f-8f20-4e2a-b98f-2a5ba7f30fcc" />

jednoduchý sinus kosinus

Inverzní osa - otočím a ozrcadlím přes střed - značky jsou ty kolečka anebo čárky se symbolem s osou

U čtyřčetné inverzní dostanu tetraedr...interesant

**BODOVÉ GRUPY URČUJÍ TVAR KRYSTALU**

Je to v umění, to jsme určovali

**obdélník** -> dvojčetná osa

Je třeba umět příslušné matice k operacím symetrie

u rotace: 
|matice rotace: | (TeX nefachá) :(|
|--------|--------|
| cos θ  | −sin θ |
| sin θ  |  cos θ |


prvky nemohu vždy libovolně kombinovat -> bodové grupy
## Bodové grupy
- buǩy vybírám aby významné osy byly podél osy c
- řád = počet prvků grupy
- umět určit počty prvků symetrie u základních těles - krychle, tetraedr, oktaedr, šestiboký hranol
- stereografická projekce
    - krystal dáme do středu kulové plochy
    - k plochám vedem kolmice - polární linie
    - polární line protnou kulovou plochu - póly
    - Udělám stereografickou projekci (to co se dělá u komplexních čísel)
    - natáhnu wulfovy síť - nejlépe aby zajímavé body byly na stejném poledníku
    - osu zóny najdu 90°od poledníku
    - zachovává úhly (ne délky)
- **grupa** je množina s operací pokud:
  1) je uzavřená (po udělání operace to padne dovnitř) - jen s tímto je to grupoid
  2) operace je asociativní
  3) existuje jednotkový prvek
  4) existuje inverze
  - příklady: celá čísla a sčítání
  - pokud je komutativita -> Abelovská
  - generátory - vygenerují celou grupu
  - cyklická - g, g^2, ... g^n=e - po násobení sám se sebou se vrátím k identitě
- Matice rotace ve 3D - umět
- kofein má jen identitu - idk asi dobrý vědět

|operace | značka|
|--------|-------|
|n-četná osa | $C_n$|
|identita | E|
|rovina symetrie | $\sigma$|
|střed symetrie | i |
|rotačně-reflexní osa | $S_n$|

- multiplikační tabulka - good to know
- osy se musí protínat - jinak by nebyl pevný bod
- průsečnice dvou rovin symetrie je osa - úhel rotace je 2*úhel mezi rovinami
- bod, kde sudá osa protíná rovinu je střed symetrie
- vět je víc, ale nebude je zkoušet
### Chytří pánové z těch vět udělali třídy symetie
1) Skupina A: - má jen jednu vícečetnou osu rotace
   
       a) udělám vícečetnou osu - n
       b) přidám kolmo na ni dvojčetné - n2, n22...
       c) přidám kolmo na ni rovinu - n/m
       d) přidám rovinu rovnoběžně - nmm
       e) přidám kolmo i rovnoběžně rovinu n/mmm
       f) jedna inverzní osa - -n
       g) jedna inverzní s kolmou dvojčetnou - -3m, -42m, -6m2
   - 27 různých symetrii
 2) Skupina B: - má 3 a 4 četnou osu zároveň
    - je to dalších 5 grup - hlavně krychle a potom další modifikace krychle

**CELKEM JE JICH 32 --- TOHLE VĚDĚT**

izomorfní grupy mají stejné multiplikační tabulky (např 2 a m)
- symtrická multiplikační tabulka - abelovská grupa
- podgrupa - část grupy co je taky grupa - sudá versus celá čísla
- nadgrupa - opak podgrupy
      - fázové transformace jsou po ose grupa -> podgrupa
<span style="color:red">Příklad:</span> určit multiplikační tabulky molekul
**bacha an nekomutativní grupy
  -shonflies se opužívá u molekul ale ne úplně 100% - viz vývojový diagram
  <img width="650" height="563" alt="image" src="https://github.com/user-attachments/assets/5ab77589-65d9-4d48-9f6b-c116c31e0168" />
  
- vědět: kdy do jaké soustavy ty grupy patří orientačně, vědět minimální symetrie grup:
  
|soustava | grupa| minimální symetrie |
|-------|--------|-----|
|triklinická | 1 | žádná |
| mooklinická | 2 | 1 dvojčetná osa podél c (občas b)|
| orthorombická (všechny úhly pravé)| | tři 2 četné osy podél a, b, c |
|trigonální (3 stejné úhly) | 3| jedna 3četná podél buňky|
| tetragonální (čtverec na podstavě, pravé úhly) | 4| jena 4 četná podél c|
|hexagonální | 6| jedna 6četnná podél c |
| kubická| kombinace 3 a 2 nebo 4|čtyři 3četné podél tělesových úhlopříček |

pořadí směrů prvků ve značení: [100], [111], [110]

<span style = "color:green"> Na tu minimální symetrii jsou dobré testové otázky <span>

Bravaisovy mříže taky dobré pamatovat - 14 dohromady
<img width="1535" height="993" alt="image" src="https://github.com/user-attachments/assets/0aa07192-fb8d-4862-a707-5f750ad68a6a" />

translace mohou být i a/2, b/2, c/2 - to potřebuju na centrované

4indexové snačení u hexagonální:
- symetricky ekvivalentní směry dostanu jen porhazováním (narozdíl od trojindexů)
- je to přeurčené - čtvrtý index je závislý [uvtw], kde t = -(u+v)
- není správné jen vypustit třetí index - občas to není dobře
- u rhomboedrické občas dělám v hexagonální
- **každá soustava má svou metricku matici**
- mezirovinné vzdálenosti jsou taky fajn vědět - 1/$d^2_{hkl}$
