# MechCombatGame
In this repository is the code source for the mech combat game i've created. The game will be presented as a project within the subject of Game Design from the Faculty of Computer Science Iasi. Also, this game will be presented as Bachelor Project at the end of the schoolar year.

Project made by Ionita Andra, group A7.


Proiectul MechCombat poarta mai nou denumirea de Gateway-Evadarea.
Folosindu-ma de contextul actual al pandemiei am gandit un personaj care urmeaza sa fie inchis, izolat, intr-o arena unde singura cale de iesire este folosind usa care inchide spatiul limitat in care acesta se afla. Insa pentru a ajunge sa deschida acea usa, jucatorul trebuie sa adune o suta de diamante pe care sa le foloseasca pentru crearea cheii la banca de mestesugarit. 
Personajul nostru depinde de trei sisteme de supravietuire constand in viata, rezistenta si energie pentru lupta. Avand in vedere ca la inceput personajul nu va detine niciun diamant, unica cale prin care acesta poata sa stranga acele diamante este sa distruga inamicii care vin sub forma de valuri. Numarul de inamici pentru fiecare val este direct proportional cu numarul valului la care jucatorul a reusit sa ajunga. 
Personajul nostru are trei abilitati pe care le poate folosi impotriva inamicilor. Imediat dupa distrugerea unui inamic, un diamant va aparea in locul in care acesta a murit. Constatand ca numarul inamicilor va creste iar viata, energia si rezistanta sunt limitate, banca de mestesugarit va permite si imbunatatirea atat a abilitatilor cat si cresterea procentuala a vietii si rezistentei. Evident toate aceste imbunatatiri vor costa diamante, astfel realizam ca jucatorul nu are nevoie doar sa doboare o suta de inamici ca sa obtina cheia, ci are nevoie de mai multe deoarece trebuie sa ia in calcul si cresterea abilitatilor. De asemenea jucatorul ar trebui sa realizeze ca orice strategie care ii va reduce total viata il va trimite pe acesta la inceputul jocului. Jucatorul castiga in momentul in care deschide poarta si reuseste sa treaca de aceasta iar jucatorul pierde atunci cand viata sa va ajunge zero.
Scopul jocului este acela de a canaliza toata frustrarea izolarii spre gandirea unei strategii care urmeaza sa imbine atat folosirea diamantelor cu cap in scopul de a ajunge cat mai repede la obiectivul cheii, cat si incercarea de a conserva viata si imbunatatirea ei cat mai mult pentru a nu risca revenirea la punctul de start a jocului.

Saptamana 3: Crearea sistemului de viata, energie, stamina si life pickere-lor. De asemenea crearea hud-ului

Saptamana 4: importarea mesh-ului pentru caracterul principal si crearea movement-ului, sprintului si crouchingului

Saptamana 5: Implementarea a unei abilitati de atac si una de healing pentru caracter. adaugarea animatiilor si a efectelor speciale pentru acestea. Implementarea unui AI care te urmareste pe harta

Saptamana 6: Adaugarea animatiilor, si mesh-ului pentur alt caracter principla. Crearea unui meniu care te lasa sa alegi cu care caracter vrei sa joci. AI-ul acum poate lua damage

Saptamana 7: Crearea unui spawner care adauga AI-uri in scena pe masura ce acestea dispar, mereu vor fi 5 AI-uri in scena. Implementarea unui abilitati default care da damage pentru AI. Sculptarea terenului si adaugarea de texturi pentru acestea.

Saptamana 8: Implementarea animatiilor de damage total a personajului principal + Prezentare

Samptamana 9: Importarea de decoratiuni pentur mediu: laptopul da crash la randare lucru care ma obliga sa iau poriectul de la 0 cu alta poveste si alte texturi

Saptamana 10: Sculptarea terenului, adaugarea de texturi, decorarea mediului cu copaci, roci, fire de iarba si flori, crearea zonei de acasa si decorarea ei, crearea arenei cu munti sculptati  care se inchid cu 2 porti. Zona de acasa va avea de asemenea porti. Crearea animatiilor pentru usile care se deschid si inchis.

Saptamana 11: Importarea personajului, Implementarea sistemului de viata, energie si putere de lupta. Crearea celor 3 abilitatilor si animatiilor pentru ele, interactiunea cu generatorul care creste viata.

Saptamana 12: Creara AI-urilor folosind algoritmul anterior de AI, importarea mesh=urilor, crearea a 2 tipuri de inamici, unul care expldoeaza si unul care arunca cu proiectile. Crearea spawnerului care ii pun random pe viata pe baza unui sistem de wave-uri care creste ca dificultate pe masura ce este finalizat cel anterior. 

Saptamana 13: Crearea interfatei de la crafting bench. Punerea textului dinamic pentru pret si actuala valoare pentru abilitatea si implementarea functionalitatilor pentru fiecare buton de plus

Saptamana 14: Crearea meniului principal, crearea imaginii cu instructiuni, arhitectura navigarii, crearea ecranelor de win si lose, punerea conditiei e a deschide gate-ul cu cheia.

Saptamana 15: Repararea bug-urilor si adaugarea muzicii.