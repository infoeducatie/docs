Criterii de jurizare - InfoEducație 2015
===============================
Secțiunea Roboti 
--------------------

- [Capitolul I. Utilitate practica](#capitolul-i-utilitate-practica-10-puncte) 10 puncte
- [Capitolul II. Mecanica](#capitolul-ii-mecanica-20-puncte) 20 puncte
    - [Secțiunea II.1. Complexitate](#secțiunea-ii1-complexitate)
    - [Secțiunea II.2. Eficienta in constructie](#secțiunea-ii2-eficienta-in-constructie)
- [Capitolul III. Electronica](#capitolul-iii-electronica-20-puncte) 20 puncte
    - [Secțiunea III.1. Complexitate](#secțiunea-iii1-complexitate)
- [Capitolul IV. Software](#capitolul-iv-software-20-puncte) 20 puncte
- [Capitolul V. Design industrial](#capitolul-v-design-industrial-15-puncte) 15 puncte
- [Capitolul VI. Prezentare](#capitolul-vi-prezentare-15-puncte) 15 puncte
- [Observaţii](#observaţii)


#Capitolul I. Utilitate practica    **10 puncte**

- Robotul trebuie sa rezolve o problema
- In ce masura lucrarea prezentata rezolva problema expusa
- In ce masura problema expusa este rezolvata mai eficient utilizand robotul decat prin alte metode 

#Capitolul II. Mecanica     **20 puncte**

##Secțiunea II.1. Complexitate
- Numar de motoare
- Grade de libertate in miscare ale diverselor componente

##Secțiunea II.2. Eficienta in constructie:
- Indeplinirea sarcinilor cu consum minim de energie
- Poseda o sursa de energie regenerabila (acumulatorii nu sunt  considerati sursa de energie, deoarece doar inmagazineaza energie). In ce masura sursa de energie satisface necesitatile robotului (timp de acumulare versus timp de functionare).

#Capitolul III. Electronica     **20 puncte**

Tipuri diferite de senzori folositi. Ce fenomene masoara fiecare, in ce intervale posibile de intrare. Cum e folosita masuratoarea pentru rezolvarea problemei. Nu incurajam folosirea nejustificata de senzori in incercarea de a obtine punctaj.

**Arhitectura**: complexitatea circuitului electronic. Documentatia va contine descrierea fiecarei componente folosita si se va justifica alegerea. Se porneste in ordine descrescatoare a complexitatii (microprocesoare/microcontrollere, circuite logice, componente electronice active). Nu se descriu componente electronice pasive.

##Secțiunea III.1. Complexitate

Se puncteaza in ordine descrescatoare:

- Robot complet autonom in mediu necunoscut
- Robot autonom in mediu cunoscut
- Robot pre-programat sa rezolve o problema cu date de intrare  variabile, conform unor specificatii (ex: line follower, maze solver)
- Robot telecomandat
- Robot pre-programat sa rezolve o problema cu date de intrare pre-definite fixe (Ex: robot pe line de linie de asamblare).


#Capitolul IV. Software  **20 puncte**

- Programe independente fara parametrizare. Utilizatorul nu poate afecta executia programului robotului.
Programe independente cu interfete utilizator (pot fi implementate prin switch-uri, potentiometre, touchscreen, etc)
- Programe care ruleaza in regim client-server cu serverul pe robot si client remote.
- Programe care ruleaza in regim client-server cu serverul remote si clientul pe robot. Robotul se conecteaza la server pentru a primi instructiuni/task-uri, informatii necesare rularii.
- Programe cu agenti care comunica si colaboreaza pentru a indeplini functiunea (un numar de minim 2 roboti colaboreaza schimband informatii intre ei).

#Capitolul V. Design industrial **15 puncte**

- Designul trebuie sa fie simplu, functional si sa permita automatizarea procesului de productie.

#Capitolul VI. Prezentare **15 puncte**

- Prezentarea scrisa. Trebuie sa contina detalii despre primele 4 sectiuni astfel incat sa se poata face punctarea (Utilitate practica, Mecanica, Electronica, Software). Pentru fiecare sectiune, argumentati cu detalii ce caracteristici indeplineste robotul construit.
- Prezentarea pe suport electronic: trebuie sa contina scheme,  diagrame, documentatie si cod sursa folosit pentru implementarea robotului, precum si o versiune PDF a prezentarii scrise. Scheme si diagrame vor fi in format PNG, SVG sau PDF.
- Demonstratia in cadrul concursului. Se va face dovada ca robotul functioneaza si ca toate aspectele continute in prezentarea scrisa sunt functionale. Se va raspunde la intrebari din parea juriului legate de prezentarea scrisa. Se va raspunde la intrebari din partea celorlalti participanti sau a observatorilor. 
- Prezentarea scrisa este la fel de importanta ca si demonstratia. E posibil ca anumite aspecte ale lucrarii sa nu poata fi evaluate in cadrul demonstratiei, dar vor fi punctate daca exista in prezentarea scrisa.    

#Observaţii

**Scopul urmarit**: incurajarea elevilor sa invete cum se construieste si cum se programeaza un robot.
Avand in vedere ca lucrarile inscrise in concurs difera extrem de mult in privinta functionalitatii implementate nu urmarim o comparatie directa intre lucrari, ci incercam sa punctam munca depusa de participant si rezultatele obtinute in relatie cu scopul propus. Bineinteles scopul in sine va influenta punctarea, o lucrare mai putin ambitioasa, de complexitate redusa, executata perfect e posibil sa fie punctata mai putin decat o lucrare de complexitate ridicata cu deficiente minore. 

Criteriile de evaluare urmaresc sa puna in evidenta cat numarul de notiuni teoretice si tehnici de implementare cunoscute si demonstrate de elevi atat in faza de implementare a lucrarii cat si la prezentarea acesteia.

Pentru fiecare dintre sectiunile de mai jos se vor acorda puncte, punctajul final fiind realizat prin insumarea punctelor pentru fiecare criteriu.
