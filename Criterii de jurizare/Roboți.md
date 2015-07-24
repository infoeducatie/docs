Criterii de jurizare - InfoEducație 2015
===============================
Secțiunea Roboti 
--------------------

- [Capitolul I. Utilitate practică](#capitolul-i-utilitate-practică-10-puncte) 10 puncte
- [Capitolul II. Mecanica](#capitolul-ii-mecanica-20-puncte) 20 puncte
    - [Secțiunea II.1. Complexitate](#secțiunea-ii1-complexitate)
    - [Secțiunea II.2. Eficiența în construcție](#secțiunea-ii2-eficiența-în-construcție)
- [Capitolul III. Electronica](#capitolul-iii-electronica-20-puncte) 20 puncte
    - [Secțiunea III.1. Complexitate](#secțiunea-iii1-complexitate)
- [Capitolul IV. Software](#capitolul-iv-software-20-puncte) 20 puncte
- [Capitolul V. Design industrial](#capitolul-v-design-industrial-15-puncte) 15 puncte
- [Capitolul VI. Prezentare](#capitolul-vi-prezentare-15-puncte) 15 puncte
    - [Secțiunea VI.1. Prezentarea scrisă](#secțiunea-vi1-prezentarea-scrisă)
    - [Secțiunea VI.2. Prezentarea pe suport electronic](#secțiunea-vi2-prezentarea-pe-suport-electronic)
- [Observaţii](#observaţii)


#Capitolul I. Utilitate practică **10 puncte**

- Robotul trebuie să rezolve o problemă
- În ce măsură lucrarea prezentată rezolvă problema expusă
- În ce măsură problema expusă este rezolvată mai eficient utilizând robotul decât prin alte metode 

#Capitolul II. Mecanica **20 puncte**

##Secțiunea II.1. Complexitate
- Număr de motoare
- Gradele de libertate în mișcare ale diverselor componente

##Secțiunea II.2. Eficiența în construcție
- Îndeplinirea sarcinilor cu consum minim de energie
- Posedă o sursă de energie regenerabilă (acumulatorii nu sunt  considerați sursă de energie, deoarece doar înmagazinează energie). În ce măsură sursa de energie satisface necesitățile robotului (timp de acumulare versus timp de funcționare).

#Capitolul III. Electronica **20 puncte**

Tipuri diferite de senzori folosiți. Ce fenomene măsoară fiecare, în ce intervale posibile de intrare. Cum e folosită măsurătoarea pentru rezolvarea problemei. 

**Atenție** *Nu încurajăm folosirea nejustificată de senzori în incercarea de a obține punctaj.*

**Arhitectura**: complexitatea și eficiența circuitului electronic. Documentația va conține descrierea fiecărei componente folosită și se va justifica alegerea. 

Se pornește în ordine descrescătoare a complexității:

- microprocesoare
- microcontrollere
- circuite logice
- componente electronice active

**Atenție** *Nu se descriu componentele electronice pasive.*

##Secțiunea III.1. Complexitate

Se punctează în ordine descrescătoare:

- Robot complet autonom în mediu necunoscut
- Robot autonom în mediu cunoscut
- Robot pre-programat să rezolve o problemă cu date de intrare  variabile, conform unor specificații (de exemplu: *line follower*, *maze solver*)
- Robot telecomandat
- Robot pre-programat să rezolve o problemă cu date de intrare pre-definite fixe (de exemplu: robot pe linie de asamblare).


#Capitolul IV. Software  **20 puncte**

- Programe independente fără parametrizare. Utilizatorul nu poate afecta execuția programului robotului.
Programe independente cu interfețe pentru utilizator (pot fi implementate prin switch-uri, potențiometre, touchscreen, etc)
- Programe care rulează în regim client-server cu serverul pe robot și client remote.
- Programe care ruleaza în regim client-server cu serverul remote și clientul pe robot. Robotul se conecteaza la server pentru a primi instrucțiuni / task-uri, informații necesare rulării.
- Programe cu agenți care comunică și colaborează pentru a îndeplini funcțiunea (un număr de minim 2 roboți colaborează schimbând informații între ei).

Se va puncta atât gradul de complexitate (un program independent va fi punctat mai bine decat unul care trebuie controlat de un operator), cât și coding style-ul(respectarea unui coding style va fi punctată suplimentar) și eficiența codului(de ex. vor fi depunctate operațiile blocante care puteau fi evitate).

#Capitolul V. Design industrial **15 puncte**

- Designul trebuie să fie simplu, funcțional și să permită automatizarea procesului de producție.

#Capitolul VI. Prezentare **15 puncte**

- Demonstrația în cadrul concursului va face dovadă că robotul funcționează și că toate aspectele conținute în prezentarea scrisă sunt funcționale. 
    - Se va raspunde la întrebări din parea juriului legate de prezentarea scrisă.
    - Se va raspunde la întrebări din partea celorlalți participanți sau a observatorilor. 
- Prezentarea scrisă este la fel de importantă ca și demonstrația.
- Este posibil ca anumite aspecte ale lucrării să nu poată fi evaluate în cadrul demonstrației, dar vor fi punctate dacă există în prezentarea scrisa.    

##Secțiunea VI.1. Prezentarea scrisă

Trebuie să conțină detalii despre primele patru secțiuni astfel încât să se poată face punctarea:

1. Utilitate practica
2. Mecanica
3. Electronica
4. Software

Pentru fiecare sectiune, argumentați detaliat ce caracteristici îndeplinește robotul construit.

##Secțiunea VI.2. Prezentarea pe suport electronic

- Trebuie să conțină scheme,  diagrame, documentație și codul sursă folosit pentru implementarea robotului, precum și o versiune PDF a prezentării scrise.
- Schemele și diagramele vor fi în format PNG, SVG sau PDF.


#Observaţii

**Scopul urmarit**: încurajarea elevilor să învețe cum se construiește și cum se programează un robot.

Având în vedere că lucrarile înscrise în concurs diferă extrem de mult în privința functionalității implementate nu urmărim o comparație directă între lucrări, ci încercăm să punctăm munca depusă de participanți și rezultatele obținute în relație cu scopul propus. Bineînteles scopul în sine va influența punctarea (o lucrare mai puțin ambițioasă, de complexitate redusă, executată perfect este posibil să fie punctată mai puțin decât o lucrare de complexitate ridicata cu deficiențe minore). 

Criteriile de evaluare urmăresc să pună în evidență numărul de noțiuni teoretice și tehnici de implementare cunoscute și demonstrate de către elevi atât în faza de implementare a lucrării cât și la prezentarea acesteia.

Pentru fiecare dintre secțiunile de mai sus se vor acorda puncte, punctajul final fiind realizat prin însumarea punctelor pentru fiecare criteriu.
