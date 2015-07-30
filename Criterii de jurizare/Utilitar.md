**Criterii de jurizare - InfoEducație 2015**
===============================
Secțiunea Software Utilitar 
--------------------

- [Capitolul I. Arhitectura aplicației](#capitolul-i-arhitectura-aplicației-25-puncte) - **25 puncte**
	- [Secțiunea I.1. Alegerea tematicii](#secțiunea-i1-alegerea-tematicii)
	- [Secțiunea I.2. Proiectarea arhitecturală](#secțiunea-i2-proiectarea-arhitecturală)
	- [Secțiunea I.3. Analiza pieței](#secțiunea-i3-analiza-pieței)
- [Capitolul II. Implementarea aplicației](#capitolul-ii-implementarea-aplicației-50-puncte) - **50 puncte**
    - [Secțiunea II.1. Eleganța implementării](#secțiunea-ii1-eleganța-implementării)
    - [Secțiunea II.2. Maturitatea aplicației](#secțiunea-ii2-maturitatea-aplicației)
    - [Secțiunea II.3. Tehnologiile folosite](#secțiunea-ii3-tehnologiile-folosite)
    - [Secțiunea II.4. Securitatea aplicației](#secțiunea-ii4-securitatea-aplicației)
    - [Secțiunea II.5. Funcționalitate](#secțiunea-ii5-funcționalitate)
    - [Secțiunea II.6. Testarea produsului](#secțiunea-ii6-testarea-produsului)
    - [Secțiunea II.7. Distribuirea rolurilor în echipă](#secțiunea-ii7-distribuirea-rolurilor-în-echipă)
- [Capitolul III. Interfața (GUI / CUI)](#capitolul-iii-interfața-gui-cui-15-puncte) - **15 puncte**
	- [Secțiunea III.1. Impresia generală](#secțiunea-iii1-impresia-generală)
	- [Secțiunea III.2. Ușurință în folosire](#secțiunea-iii2-ușurință-în-folosire)
- [Capitolul IV. Prezentarea proiectului](#capitolul-iv-prezentarea-proiectului-10-puncte) - **10 puncte**
	- [Secțiunea IV.1. Impresia generală a proiectului](#secțiunea-iv1-impresia-generală-a-proiectului)
	- [Secțiunea IV.2. Documentația proiectului](#secțiunea-iv2-documentația-proiectului)
- [Capitolul V. Resurse obligatorii](#capitolul-v-resurse-obligatorii)
	- [Secțiunea V.1. Codul sursă](#secțiunea-v1-codul-sursă)
	- [Secțiunea V.2. Resurse externe](#secțiunea-v2-resurse-externe)
- [Observatii](#observatii)


#Capitolul I. Arhitectura aplicației - **25 puncte**

În cadrul acestui capitol vom urmări toți pașii urmați în dezvoltarea proiectului propus.

##Secțiunea I.1. Alegerea tematicii
Această secțiune va puncta originalitatea ideii propuse, perspectiva în care a fost abordată tematica și maniera în care aduce beneficii publicului țintă.

##Secțiunea I.2. Proiectarea arhitecturală
Poate unul dintre cei mai importanți pași în dezvoltarea unei aplicații este proiectarea arhitecturală. În cadrul acestui pas se alege maniera de implementare a proiectului dar și tehnologiile ce avantajeaza dezvoltarea acestuia.

Aspecte ce pot fi punctate:

 - alegerea tehnologiilor potrivite pentru acest tip de proiect.
 - folosirea paradigmelor de programare obiectuală şi/sau funcţională, acolo unde este cazul.
 - folosirea unor tehnologii open source.
 - crearea unor noi servicii/tehnologii.

##Secțiunea I.3. Analiza pieței
După alegerea unei tematici, dezvoltatorul trebuie să se documenteze referitor la proiecte asemănătoare sau la maniere alternative de implementare.

În cazul în care soluția dezvoltatorului nu aduce nici un beneficiu în plus, aplicația reprezintă doar o reimplementare iar această secțiune nu va fi punctată.

Aspecte ce pot fi punctate:

- în cazul aplicațiilor ce abordează o soluție deja existentă:
	- elementele distinctive față de aplicațiile existente.
	- modalitățile inovative de abordare a problemelor impuse de aplicație.
	- inovațiile aduse asupra soluției abordate.
- în cazul aplicațiilor ce vin cu o idee nouă:
	- fezabilitatea proiectului pe termen scurt / lung.
	- existența unui public țintă bine definit.


#Capitolul II. Implementarea aplicației - **50 puncte**

##Secțiunea II.1. Eleganța implementării
Încurajăm dezvoltatorii să proiecteze și să implementeze aplicația într-o manieră care să le faciliteze posibilitatea extinderii cu ușurință a funcționalităților aplicației cu o cât mai mică intervenție asupra codului scris.

##Secțiunea II.2. Funcționalitate
O aplicație trebuie să fie proiectată în așa fel încât să poată fi folosită cât mai ușor și eficient de către utilizatorii pentru care a fost creată. În acest scop, putem puncta următoarele:
	- posibilitatea de a folosi aplicația pe cât mai multe din dispozitivele folosite de public țintă ales.
	- posibilitatea arhitecturii de a fi portată cu ușurință de pe o platformă pe alta (dacă aplicația este destinată să fie cross-platform).
	- aplicația să se adapteze la diverse rezoluții, în funcție de dispozitiv, platformă și parametrii acesteia, având grijă ca aplicația să nu necesite resetarea pentru a obține această funcționalitate (acolo unde este cazul).
	- cât de eficient și responsabil se utilizează resursele sistemului (CPU, RAM etc).
	- cât de bine sunt folosiți senzorii disponibili atunci când este cazul (accelerometru, giroscop, GPS).
	- cât de eficient și responsabil sunt folosite capabilitățile de networking (WIFI direct, Bluetooth, infraroșu etc).
	- posibilitatea de a oferi un minim de funcționalitate în cazul pierderii conexiunii la internet (acolo unde este cazul).
	- eficiența comunicării prin canale externe, acolo unde este cazul (folosirea unui cache, folosirea unor cereri de tip batch etc).

##Secțiunea II.3. Tehnologiile folosite
În vederea evaluării acestui criteriu se va ține cont atât de necesitatea folosirii fiecărei tehnologii în realizarea proiectului, cât și de alegerea tehnologiilor potrivite pentru aplicația prezentată.

##Secțiunea II.4. Securitatea aplicației
În cadrul acestei secțiuni se va urmări modalitățile abordate de autori pentru a evita executarea de scenarii nedorite în cadrul aplicației.

Elemente ce pot fi punctate:
- Validarea datelor de intrare și mecanisme de prevenție și protecție împotriva diverselor vulnerabilități (injecții, părăsirea sandbox-ului, escaladarea privilegiilor etc).
- Tratarea erorilor și a excepțiilor.
- Mecanisme de detecție și, eventual, blocare a atacurilor.

**Atenție** - Această secțiune va fi punctată direct proporțional cu complexitatea și necesitatea de securitate a aplicației.

##Secțiunea II.5. Testarea produsului
În cadrul dezvoltării unui proiect, există posibilitatea apariției unor probleme sau scenarii neprevăzute în cadrul etapei de dezvoltare arhitecturală.

Elemente ce pot fi punctate în această secțiune:

- Modalitățile de testare funcțională a proiectului (unit testing, integration testing, etc).
- Modalitățile de testare non-funcționale ale proiectului (scalabilitate, performanță, securitate, portabilitate pe platforme multiple etc).
- Eventuale defecțiuni ale sistemelor de care proiectul depinde (internet, baza de date, etc).
- Modalități de automatizare a întregului proces de testare.


##Secțiunea II.6. Maturitatea aplicației
În cadrul acestei secțiuni se va evalua starea în care se află aplicația și cât de aproape este aceasta pentru a putea fi distribuită publicului țintă.

Elemente ce pot fi punctate:
- viziunea aplicatiei in conformitate cu publicul tinta ales.
- stadiul său, relativ la fiecare secțiune.
- utilizarea aplicației în lumea reală de către publicul țintă.


##Secțiunea II.7. Distribuirea rolurilor în echipă
Pentru a putea evidenția contribuția fiecărui membru din echipă, este obligatorie folosirea unui sistem de versionare (GIT / SVN).
**Atenție** - Orice echipă ce nu folosește un sistem de versionare nu va putea participa în concurs!

#Capitolul III. Interfața (GUI / CUI) - **15 puncte**
Orice aplicație trebuie să ofere o modalitate elegantă de a expune funcționalitățile oferite clientului.

În cadrul unei aplicații web acestă secțiune se referă la componenta frontend.

##Secțiunea III.1. Impresia generală
Interfața trebuie să ofere publicului țintă accesul la operația / resursa dorită în cel mai simplu mod.

##Secțiunea III.2. Ușurință în folosire
Interfața trebuie să fie plăcută, intuitivă și ușor de parcurs (UI, UX).

#Capitolul IV. Prezentarea proiectului - **10 puncte**
În cadrul acestei secțiuni se vor puncta elemente ce țin de prezentarea și distribuirea proiectului.

##Secțiunea IV.1. Impresia generală a proiectului
Vor fi punctate elemente ce țin de maniera de prezentare și justificare a necesității unui astfel de proiect. De exemplu:

- website de prezentare.
- film de prezentare a proiectului.
- alte materiale menite să promoveze proiectul.

##Secțiunea IV.2. Documentația proiectului
În documentația proiectului vă sugerăm să punctați următoarele aspecte:

- Abstract:
	- o descriere scurtă și exactă asupra scopului aplicației și a principalelor funcționalități.
- Prezentarea funcționalităților aplicației.
- Arhitectura aplicației.
- Elemente distinctive ale aplicației / puncte forte.
- Ghid de instalare și configurare a aplicație.
- Raspunsuri de cel putin un paragraf pentru urmatoarele intrebari:
	- Justificarea folosirii tehnologiilor alese.
	- Opinia autorului/autorilor despre ideea ce stă la baza proiectului implementat, dar și utilitatea acestuia pentru publicul ei țintă (minim 1 exemplu).


#Capitolul V. Resurse obligatorii
Următoarele resurse nu trebuie să lipsească din pachetul pe care participanții îl vor oferi juriului. În cazul în care aceste resurse lipsesc, proiectul nu va putea fi jurizat. Prin resurse înțelegem codul sursă împreună cu bibliotecile și fișierele necesare compilării și funcționării.

##Secțiunea V.1. Codul sursă
Maniera în care este structurat codul sursă este foarte importantă în dezvoltarea unei aplicații. Cu cât aplicația este scrisă într-o manieră mai organizată și elegantă cu atât se va putea dezvolta pe viitor mai ușor.

Elemente ce pot fi apreciate:

- structurarea și folosirea standardelor de programare în limbajele alese pentru implementare.
- prezența docstring-urilor și a comentariilor ce descriu funcționalitatea fragmentelor de cod.
- ușurința prin care se poate desfășura procedeul de mentenanță a codului și design pattern-urile folosite.

##Secțiunea V.2. Resurse externe
În cadrul acestei secțiuni autorii trebuie să ofere o listă de resurse externe pe care le-au folosit în dezvoltarea aplicației.

Printre acestea putem menționa:

- fragmente de cod ce nu vă aparțin.
- biblioteci folosite.
- alte elemente ce aparțin unei alte terțe.

#Observații
- Aplicațiile înscrise ce conțin alte funcționalități, în afara celor declarate (cod malițios), vor fi descalificate.
- Folosirea unor resurse externe ce nu sunt declarate odată cu predarea proiectului va duce, după caz, la depunctarea sau chiar descalificarea participanților din concurs.
- Orice tentativă de fraudă (spre exemplu, copierea unui proiect) va duce la descalificarea proiectului din concurs.
- **Atenție** - Punctajele acordate pentru capitolul [I. Arhitectura aplicației](#capitolul-i-arhitectura-aplicației-30-puncte) și [II. Implementarea aplicației](#capitolul-ii-implementarea-aplicației-40-puncte) **sunt direct proporționale cu complexitatea și amploarea proiectului dezvoltat**. 
