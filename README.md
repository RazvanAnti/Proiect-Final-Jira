# Proiect-Final-Jira


# 1. Sectiunea de testare, aspecte de business si management

Scopul proiectului al cursului de Testare Manuala si Automata este utilizarea tuturor cunostintelor tehnice dobandite de-a lungul cursului si utilizarea lor in cazuri practice, intalnite in activitatea de zi cu zi.

* Site testat: [OpenCart](https://docs.opencart.com/en-gb/introduction/)

* Documentatia API: [OpenCart.API](https://docs.opencart.com/en-gb/system/users/api/)

Proiectul prezinta 3 sectiuni principale, acestea facand referire la planul de testare, obiective si aspecte de business/management, dar si afisarea, respectiv analizarea tehnicilor de testare, bug-urilor, story-urilor din Jira.

Tehnologii utilizate: Jira, Zephyr. Pentru utilizarea platformei Jira s-a folosit contul ItFactory. De asemenea, a fost necesara si instalarea plug-in-ului Zephyr prin logarea ca Administrator, accesarea meniului Jira si selectarea optiunii Apps, Find New Apps, s-a cautat Zephyr for Jira si s-a accesat rezultatul cautarii. Apoi s-a instalat plug-in-ul. De asemenea, proiectul in cauza s-a folosit si de documentatia API a website-ului, link-ul fiind furnizat mai sus.             

Specificatii functionale:
-> Pentru a putea crea si gestiona proiectul in cauza, s-a apela la progamul de tracking management Jira, adaugand plug-in-ul Zephyr in vederea unei utilizari targetate pe testare.
Ca specificatii funtionale in Jira, s-au utilizat urmatoarele: Issue tracking, workflow-uri costumizabile, project management, custom fields, dashboard si rapoarte.

* Ca principal epic avem: Store Front Module: modul care consta in interfata cu care clientul interactioneaza cu magazinul. Modulul cuprinde 7 story-uri: The header. The top menu. Slideshow. Footer. Product pages. Product compare. Shopping cart page.

Exemplu de story creat in scopul proiectului: 'Shopping Cart PAge'
![image](https://github.com/RazvanAnti/Proiect-Final-Jira/assets/165046399/113f1570-24f9-4080-b20f-8445978c864b)

* Pentru a putea urmari story-urile in dataliu: [PDF.Stories](https://github.com/RazvanAnti/Proiect-Final-Jira/blob/main/Stories.pdf)


# 2. Procesul de Testare 

## 2.1. Test Planning

### Planul de Testare

Planul de testare a fost creat pentru a putea detalia testarea principalelor si celor mai importante functionalitati ale site-ului Open cart.

Planul identifica sectiunile si itemii de testare, functionalitatile de tipurile de teste, personalul, resursele si timpul implicate, incluzand si riscul asociat cu planul in cauza. Scopul documentului este deci acoperirea intregului plan de testare pentru website-ul OpenCart. Asadar pe langa cele mentionate mai sus, mentionam din nou planul, analiza, design-ul, implementarea, executia, finalizarea, sesiunile de monitorizare si control. Merita amintite si criteriile de intrare si iesire.

### Impartirea rolurilor si responsabilitatilor


| Nume tester         | Responsabilitati            |
| -------------       | ----------------------------|
| Anti Razvan-Ionut   | "Admin Interface", "Catalog"|
| Adam Eduard-Marius  | "Extensions", "Sales"       |
| Popa Diana-Maria    | "Marketing", "System"       |
| Damatarc Marian     | "Tools", "Reports"          |


### Definirea criteriilor de intrare

Dat fiind domeniul de activitate al clientului, este important ca platforma sa faciliteze o experienta placuta si intuitiva de utilizare, o performanta sporita, dar si securitate si functionalitati disponibile.

#### Impartirea de roluri in cadrul echipe de testare

#### Definire si finalizare plan de testare

#### Identificare cerinte de business

#### Identificare si dezvoltare riscuri de proiect

- Întârzierea lansării website-ului din cauza unor neclarități în specificațiile cerințelor.
- Lipsa de claritate în cerințe poate determina echipa de dezvoltare să implementeze o funcționalitate diferită de ceea ce și-a imaginat clientul.
- O prelungire a timpului de lansare din cauza întârzierilor în implementarea unui sistem de procesare a plăților de către un furnizor terț.


### Definirea criteriilor de iesire
- 75% dintre teste vor trece, avand statusul "Passed"
- Nu vor exista probleme critice in niciunul dintre modulele care are statusul Open
- testele ulterioare sunt 100% "Passed" (trebuind sa ne asiguram ca testele introduse anterior nu vor da peste cap functionalitatile site-ului).

### Test scope
Teste în domeniul de aplicare:
Includem aici modulele asupra carora s-a agreat aplicarea planului si strategiei de testare: Admin Interface, Catalog, Extensions, Sales, Marketing, System, Tools, Reports.

Teste in afara domeniului de aplicare:
Amintim testele non-functionale precum cele de stres, performanta, dar si alte teste in afara scopului care vor fi descoperite ulterior pe derularea proiectului.
Nu va axista QA support pentru versiunea de mobil a site-ului, respectiv aplicatia, testarea rezumandu-se doar la pagina web a clientului.
Testarea automata este de asemenea in afara domeniului de aplicare.

### Riscurile asociate

<b>Riscurile de proiect</b>:

Riscurile de proiect care pot aparea in general intr-un proiect de testare software pot sa fie, de exemplu, urmatoarele:

- Resursele insuficiente se refera fie la lipsa de personal si de timp in vederea realizarii testarii in profunzime/tuturor defectelor.
- Stabilirea unui program neclar sau instabil reprezinta un risc asociat tehnicii agile. Un risc probabil mai ales in cazul unor termene limita stranse, care pot veni in completarea la numeroase schimbari in cerinte (testare incompleta sau chiar superficiala).
- Problemele de comunicare sau posibila incompatibilitate de a exprima clar notiuni de natura tehnica, importante de altfel pentru serviciile clientului.
- Competentele reduse ale personalului, un risc posibil mai ales in cazul in care se descopera o multitudine de defecte si bug-uri complexe.

Specific proiectului pe care l-am realizat, am identificat urmatoarele riscuri de proiect: 

- Întârzierea lansării website-ului din cauza unor neclarități în specificațiile cerințelor.
- Lipsa de claritate în cerințe poate determina echipa de dezvoltare să implementeze o funcționalitate diferită de ceea ce și-a imaginat clientul.
- O prelungire a timpului de lansare din cauza întârzierilor în implementarea unui sistem de procesare a plăților de către un furnizor terț.


### Evaluarea criteriilor de intrare

#### In urma implementarii planului de testare, criteriile de intrare au fost atinse, iar procesul poate continua, el putandu-se modifica datorita abordarii de tip agile. 

## 2.2 Monitorizare si control

Monitorizarea si controlul s-a realizat generand rapoarte periodice care sa coincida cu statusul curent al testelor. Astfel, s-au facut comparatii cantitative si masurabile ale planului original cu progresul testarii, s-a verificat si analizat status report-ul, adaugarea de teste aditionale unde a fost necesar (conform evolutiei proiectului si cerintelor ulterioare ale clientului, luand bineinteles in calcul renegocierea timpului de livrare si a pretului proiectului).

![image](https://github.com/RazvanAnti/Proiect-Final-Jira/assets/165046399/1bb16c3f-d179-44f2-8be0-7e0e2f2b101d)


## 2.3 Test Analysis

Conform planului de testare, dar si prin documentatia primita de la client, s-au elaborat si testat de business, specificatiile de design, in vederea imbunatatirii loc, inlaturarea generalitatilor si ambiguitatilor, contradictii. Concret, aceasta etapa a fost una de early testing, in care s-a discutat cu specialistii care sunt modulele cu impact cel mai mare asupra clientului.


### 2.3.1 Functionalitati si conditii de testare

Mai jos se pot regasi functionalitatile care au fost extrase pentru testare:

1. Testarea directionarii clientului catre sectiunea de Shopping Cart - pentru o rata de conversie mai buna
2. Directionarea clientului catre Checkout - pentru a scurta customer jurney
3. Top Menu este afisat pe fiecare pagina - pentru a avea un UI  intuitiv si rapid
4. Pagina produsului contine sectiubea de detalii despre produs - pentru a creste interesul si dorinta de cumparare
5. Pagina de produs afiseaza sectiunea de rating - pentru a spori gradul de incredere
6. Pagina produsului contine si afiseaza comparatia cu alte produse - pentru a oferi clientului posibilitatea unei achizitii informate si orientate spre interese
7. Produsele dispun de optiunea de Share - pentru a spori rata de conversie
8. Produsele au fost adaugate in cos din sectiunea de comparatie - pentru a mari pool-ul de potentiale produse cumparate
9. Sectiunea cosului de cumparaturi ofera un rezumat al produsului selectat - pentru a nu forta clientul sa paraseasca sectiunea de cumparare
10. Clientul are optiunea adaugarii unui cupon in sectiunea de shopping cart - pentru a incuraja achizitionarea mai multor produse, a oferi o experienta de achizitie completa pe care o poate gasi la competitie. 

#### In urma functionalitatilor de mai sus s-au definit urmatoarele conditii de testare:

Checking if all fields can be successfully filled according to the specifications without creating user login

Checking if all fields can be successfully filled according to the specifications and also create user login

We're verifying if that by clicking on the logo, we're successfully redirecting the client back to the home page

Changing the currency of the store products from the currency button

The customer has an option to add a coupon code in the Shopping Cart

Verifying if the shopping cart displays the number of items purchased and the total price of the order

Testing if the Shopping cart button will contain all the products added to the cart

Verifying if that by clicking on the Shopping Cart button, both "View Cart" or "Checkout" will appear


## 2.4 Test Design

Test case-urile pentru website au fost create folosind Zephyr Squad. In urma analizei specificatiilor tehnice, designului de testare a acoperit test case-uri pentru modulul Store Front.

Modulul Store Front este parinte pentru o serie de 36 de teste, acestea avand prioritate medie. 

Test case-urile menționate verifică funcționalitățile esențiale ale site-ului OpenCart, inclusiv completarea datelor, crearea de conturi, redirecționarea către pagina principală, schimbarea valutei, utilizarea cupoanelor de reducere, afișarea informațiilor în coșul de cumpărături și funcționalitatea butonului de coș de cumpărături.


 ## 2.5 Test Implementation

Pentru ca etapa executarii testelor sa poata inceapa, avem nevoie de prezenta unor elemente importante:
Crearea unor preconditii aferente fiecarui test case

Stabilirea prioritatilor pentru teste

Legarea testelor la cerintele de business si epicuri si stabilirea de fixed version

Descrierea pasilor unui test case, aici adaugand si test data, dar mai ales rezultatele testului

Adaugarea unor sub-task-uri aferente test case-urilor acolo unde va fi necesar.


## 2.6 Test Execution

Test case-urile au fost executate prin Zephyr Squad si pot fi analizate: [Test Cases](https://github.com/RazvanAnti/Proiect-Final-Jira/blob/main/test%20case%20final.pdf)

Bug-urile generate in urma executarii testelor: [Bugs](https://github.com/RazvanAnti/Proiect-Final-Jira/blob/main/Bugs.pdf)

Bugs:
* Search box does not return the products that was searched it return an Error

* Contact emergency can be added with an incorect type of mobile phone number

* The sub-categories for the parent category are not displayed when the mouse is dragged over it

* The parent category page did not oppens when is clicked

* Clicking on the second banner from the Slideshow did not oppend the product`s page, did not open any page

* Clicking on the second banner from the Slideshow did not oppend the product`s page, did not open any page

## 2.7 Test Completion

Criteriile de iesire au fost evaluate si adaptate in functie de modificarile ulterioare, astfel incat, estimarile au suferit modificari si limite de timp si accesabilitate. Testele create ulterior au statusul Passed, iar defectele critice au fost inchise si documentate.

* Matricea trasabiliatii a fost generata:

![image](https://github.com/RazvanAnti/Proiect-Final-Jira/assets/165046399/ff9bc147-7698-4916-8f3d-ad87fa535102)


* Test execution chart a fost generat pentru versiunea 3.0.2.0, iar acesta indica un pass rate de 75% (27 teste) dintr-un total de 36 de teste. Dintre acestea, 9 au statusul Fail.

* 7 Story-uri in total, asociate cu 21 de subtask-uri. 2 story-uri asociate cu 4 test case-uri 

Story: Product Pages --> The product page contains Product details section, The product page contains Description tab section.

Story: Shopping Cart Page --> Links the customer to the Shopping Cart, Links the customer to the Checkout.

* 36 de teste scrise, din care 36 de teste executate.

* 10 bugs detectate:

 0 bug-uri prioritate ridicată, 6 medie, 4 redusă

 0 severitate ridicată, 7 medie, 3 redusă


## 3. Concluzie
In urma analizei defectelor, nu există bug-uri care pot duce la riscul unui impact ridicat în ceea ce privește imaginea de brand, decizia de cumpărare sau pierderea de clienți.

Totuși, există bug-uri care îngreunează experiența de utilizare a clientului final, interacțiunea cu produsele. Impact de natură UI/UX conține 7 bug-uri cu severitate medie, 6 dintre acestea având un grad mediu de prioritate, 1 prioritate redusă.

Impactul cel mai redus s-a regăsit la aspecte precum imagini poziționate incorect, detalii suplimentare despre branch-ul unor produse. Regăsim 3 bug-uri cu severitate redusă, toate având prioritate redusă.

![image](https://github.com/RazvanAnti/Proiect-Final-Jira/assets/165046399/92b0e0df-ec0d-478c-9c3b-ee9b693acf27)

Luam totodata in calcul si o serie de riscuri de produs, asociate domeniului in careclientul isi desfasoara activitatea. Dintre acestea amintim riscurile de produs care sunt in stransa legatura legate de proiectul de testare in cauza. Aceasta analiza a riscurilor de produs vine in intampinarea unor viitoare strategii de dezvoltare.

- Posibilitatea existentei unor defecte nedeclarate anterior: mai exact neidentificarea unor defecte cu un grad sporit de importanta, defecte care pot impacta consistent nivelul de calitate al produsului.
- Alte riscuri de securitate care vor aparea mai ales atunci cand atacurile cibernetice vizeaza website-ul clientului.
- Fiabilitatea redusa a aplicatiei, riscul de crush frecvent, mai ales in perioadele in care exista cerere mare pe piata.

Specific produsului, intalnim riscuri de produs precum:

- Furtul datelor de carduri de credit din cauza unei vulnerabilități de securitate în sistemul de procesare a plăților.
- O rată mare de abandon a site-ului din cauza unui timp de încărcare prelungit al paginilor de produs.
- Implementarea unei funcționalități care nu corespunde cu ceea ce și-a imaginat clientul din cauza unei comunicări neclare.
- Un serviciu de livrare întârzie livrarea comenzilor din cauza unor probleme tehnice la nivelul infrastructurii lor.

Se recomanda analiza riscurilor de produs si includerea lor intr-un plan de dezvoltare ulterior. Prezentarea acestora unei echipe de testare capabila sa minimizeze sau chiar sa le elimine.
