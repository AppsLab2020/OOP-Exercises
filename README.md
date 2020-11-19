# OOP-Exercises

## Open-Lab-10.00 (30 XP)
Úvodne cvičenie na vytvorenie si GitHub repozitára.
1. Vytvorte vo Visual Studio nový konzolový C# projekt a nazvite ho "Open-Lab-10.00".
2. Doinštalujte a nastavte si vo Visual Studio GitHub Extension.
3. Uploadnite svoj projekt na GitHub - vytvorte repozitár a push-nite projekt.
4. Synchronizujte a upravujte projekt toľkokrát, aby posledný Commit ukazoval len zmenu textu v Console.WriteLine() v Main().
5. Pošlite link na repozitár Lab masterovi s číslom tejto úlohy.

## Open-Lab-10.01 (20 XP)
Vytvorenie si vlastnej triedy a objektu z nej.
1. Upravte posledné cvičenie "Open-Lab-10.00" tak, že ho rozšírite o nasledujúce veci.
2. V projekte vytvorte vlastnú triedu ku predgenerovanej triede Program v Program.cs, ktorá sa bude volať "Book".
3. V triede Book vytvorte dve premenné / atribúty / dátové objekty / fieldy: "string title" bude verejná a "int pages" bude súkromná.
4. Vytvorte v metóde Main() objekt "LOTR" z triedy Book a nastavte všetky dostupné premenné.
5. Pomocou Console.WriteLine() vypíšte všetky dostupné premenné z objektu LOTR.
6. Synchronizujte projekt tak, aby posledný Commit ukazoval len zmenu v súbore Program.cs.
7. Pošlite link na repozitár Lab masterovi s číslom tejto úlohy.

## Open-Lab-10.02 (20 XP)
Volanie metód a nastavenie prístupu (zapúzdrenie).
1. Upravte posledné cvičenie "Open-Lab-10.01" tak, že ho rozšírite o nasledujúce veci.
2. Upravte triedu Book tak, aby všetky premenné boli privátne.
3. Doplňte premenné triedy o "category", "author", "releaseDate".
4. Pre každú premennú vytvorte vlastnú verejnú metódu na zápis údaju doň.
5. Vytvorte spoločnú verejnú metódu, ktorá vypíše na obrazovku všetky údaje z premenných triedy.
6. Nastavte pomocou metód objektu LOTR všetky premenné.
7. Z objektu zavolajte metódu pre výpis údajov.
8. Synchronizujte projekt tak, aby posledný Commit ukazoval len zmenu v súbore Program.cs.
9. Pošlite link na repozitár Lab masterovi s číslom tejto úlohy.

## Open-Lab-10.03 (20 XP)
Práca s vlastnosťami (properties).
1. Upravte posledné cvičenie "Open-Lab-10.02" tak, že ho rozšírite o nasledujúce veci.
2. Upravte triedu Book tak, aby ste pre všetky premenné vytvorili verejné vlastnosti (properties) pre čítanie i zápis.
3. Vlastnosť "ReleaseDate" nastavte tak, aby nastavila premennú na "-1", pokiaľ sa zadá hodnota mimo rozsah (1450-2021).
4. Vlastnosť "Pages" nastavte tak, aby nastavila premennú na "1", pokiaľ sa zadá záporná hodnota.
5. Upravte program v Main() tak, aby sa zadávali údaje do objektu LOTR len pomocou vlastností.
6. Vypíšte na obrazovku údaje všetkých premenných z objektu pomocou vlastností, nie metódy.
7. Synchronizujte projekt tak, aby posledný Commit ukazoval len zmenu v súbore Program.cs.
8. Pošlite link na repozitár Lab masterovi s číslom tejto úlohy.

## Open-Lab-10.04 (19 XP)
Práca s konštruktorom a preťaženie metód.
1. Upravte posledné cvičenie "Open-Lab-10.03" tak, že ho rozšírite o nasledujúce veci.
2. Upravte triedu Book tak, že ju rozšírite o tri konštruktory.
3. Prvý konštruktor bude bezparametrický a nastaví všetky premenné na hodnotu -1 (texty i čísla).
4. Druhý konštruktor bude očakávať 2 parametre - názov knihy a počet strán. Tieto parametre nastavia príslušné premenné, ostatné sa nastavia na -1.
5. Tretí konštruktor bude očakávať toľko parametrov, koľko je premenných. Tieto parametre nastavia príslušné premenné.
6. V metóde Main() vytvorte nové tri objekty (LOTR2, LOTR3, HOBIT). Pri vytváraní objektov využite vždy iný konštruktor.
7. Z týchto objektov zavolajte metódy na vypisovanie údajov premenných.
8. Synchronizujte projekt tak, aby posledný Commit ukazoval len zmenu v súbore Program.cs.
9. Pošlite link na repozitár Lab masterovi s číslom tejto úlohy.

## Open-Lab-10.05 (19 XP)
Práca so statickým modifikátorom.
1. Upravte posledné cvičenie "Open-Lab-10.04" tak, že ho rozšírite o nasledujúce veci.
2. Upravte triedu Book tak, že ju rozšírite o verejný statický list stringov s názvom "categoryList";
3. Tento list inicializujte položkami "detské", "romantické", "náučné", "sci-fi", "dobrodružné".
4. Nad tento list (a všetky vlastnosti) použite trojlomítkový zápis komentára, ktorý popisuje daný dátový objekt.
5. Upravte vlastnosť "Category" tak, že bude obsahovať len možnosť "set".
6. Upravte Main() tak, že ešte pred zavolaním metódy na vypisovanie údajov premenných, nastavíte v objekte HOBIT položku category priradením údaju z categoryList.
7. Synchronizujte projekt tak, aby posledný Commit ukazoval len zmenu v súbore Program.cs.
8. Pošlite link na repozitár Lab masterovi s číslom tejto úlohy.

## Open-Lab-11.00 (35 XP)
Využitie dedičnosti.
1. Vytvorte vo Visual Studio nový konzolový C# projekt a nazvite ho "Open-Lab-11.00".
2. Uploadnite ho na GitHub do príslušného repozitára.
3. V projekte vytvorte dva nové súbory (typu class - prípona .cs) a nazvite ich "Book" a "Library".
4. Do triedy Book nakopírujte z cvičenia 10.05 všetky premenné (private), ich vlastnosti (public), statický list (public), tri konštruktory, metódu na výpis premenných (public).
5. V triede Library vytvorte premenné "numberOfBooks", "numberOfStudents", "studentsList" (list stringov), "booksList" (list Bookov) a k nim príslušné metódy pre vkladanie i výpis.
6. V metóde Main() vytvorte objekt "schoolLibrary" z triedy Library. V ňom vytvorte dvoch študentov "John" a "Poul", ktorý budú mať každý po dve učebnice. Zmysluplne vyplňte všetky premenné.
7. Z objektu schoolLibrary zavolajte metódu na vypísanie všetkých premenných.
8. Synchronizujte projekt s GitHub a pošlite link na repozitár Lab masterovi s číslom tejto úlohy.


