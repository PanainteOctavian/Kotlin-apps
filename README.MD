# Proiecte și Laboratoare de Programare

---

## Lab 1: Java și Git ☕
* **Tema:** Calculator de bază pentru expresii matematice.
* **Tehnologii:** Java, Interfață grafică **JFrame**.

---

## Lab 2: GraalVM - Programare Poliglotă 
* **Tema:** Exemplu de program poliglot care conține cod din mai multe limbaje de programare.
* **Necesitate:** Importarea și utilizarea **GraalVM** pentru execuție.

---

## Lab 3: ADT (Algebraic Data Types) în Kotlin 
* **Tema:** Program simplu de expresii regulate (**regex**) pentru ștergerea spațiilor multiple, **backspace** sau a paginii index.

---

## Lab 4: Principii SOLID (S.O.L.I.D.) 
Proiecte bazate pe aplicarea principiilor: **S**ingle Responsibility, **O**pen/Closed, **L**iskov Substitution, **I**nterface Segregation, **D**ependency Inversion.

* ### Pb 1: Web Crawler 
    * **Implementare:** Un **web crawler** (spider sau bot) care navighează automat pe internet și colectează informații.
    * **Tehnologii:** Librăriile **khttp** și **Jsoup**.
* ### Pb 2: Aplicație Cinema 
    * **Tema:** O aplicație pentru cumpărarea biletelor la un cinematograf, construită cu respectarea principiilor **SOLID**.
* ### Pb 3: Aplicație To-Do 
    * **Tema:** O aplicație simplă de tip **to-do list**, bazată pe principiile **SOLID**.

---

## Lab 7: Colecții și Generice în Kotlin 

* ### `MainLab.kt` (Loguri de Sistem) 
    * **Tema:** Program care procesează toate intrările din fișierul de log al sistemului (`/var/log/syslog`) din ultimele **30 de minute**.
* ### `MainTema.kt` (Istoric APT) 
    * **Tema:** Program care procesează ultimele **50 de linii** din fișierul de istoric al pachetelor (`/var/log/apt/history.log`) pe sistemele bazate pe Debian/Ubuntu.

---

## Lab 8: Design Patterns în Kotlin 

* ### Tema 1: Poartă Logică AND 
    * **Tema:** Aplicație care calculează ieșirea unei porți logice **AND** cu **2, 3, 4 și 8 intrări**.
* ### Tema 2: Browser cu Control Parental 
    * **Tema:** Browser care combină trei *Design Patterns* pentru funcționalități avansate:
        * **Prototype:** Pentru generarea cererilor standard.
        * **Proxy:** Pentru filtrarea cererilor HTTP GET (control parental).
        * **Facade:** Pentru o interfață de utilizator simplificată.

---

## Lab 10: Corutine (Kotlin) și Concurență (Java) ⚡

Aplicații realizate în scop academic, utilizând **Kotlin coroutines**, **Java BlockingQueue** și **Java Executors**.

| Proiect | Descriere (Kotlin Coroutines) | Descriere (Java Threading) |
| :--- | :--- | :--- |
| **P2** | Demonstrarea **pattern-ului Pipeline** utilizând corutine și **channels** pentru procesarea vectorilor în etape secvențiale. | Pipeline de procesare a vectorilor implementat cu mecanisme tradiționale de *threading* Java și **BlockingQueue**. |
| **P3** | Ilustrarea **condițiilor de cursă** (*race conditions*) la modificarea structurilor de date partajate fără sincronizare. | Implementare corect sincronizată **Producător-Consumator** utilizând **LinkedBlockingQueue** din Java. |
| **P4** | Cititor de fișiere bazat pe corutine Kotlin cu *dispatchers* I/O adecvați pentru operații asincrone. | Soluție concurentă de citire a fișierelor utilizând un *fixed thread pool executor* din Java. |
| **P5** | Pipeline de *web scraping* construit cu **actori** Kotlin: descărcare pagini, parsare conținut și randare arbore DOM. | Pipeline de procesare web în trei etape, implementat cu *threads* Java și *blocking queues*. |

---

## Lab 12: Programare Funcțională (FP) 
Paradigmă axată pe transformarea datelor cu expresii (de preferat, fără efecte secundare - *side effects*).

* ### P1: Transformări Secvențiale 
    * **Tema:** Funcție care aplică transformări secvențiale unei liste de numere întregi și calculează suma finală.
* ### P2: Cifrului Caesar Selectiv 
    * **Tema:** Implementare selectivă a cifrului Caesar care criptează conținutul fișierelor pe baza unor criterii specifice.
* ### P3: Calculator Perimetru Poligon 
    * **Tema:** Calculează perimetrul unui poligon, ordonând mai întâi punctele în secvență orară sau antiorară înainte de a măsura distanțele.
* ### P4: Functori și Manipulări 
    * **Tema:** Demonstrarea operațiilor de tip **functor** aplicate pe structuri de tip *Map* și manipulări de șiruri de caractere (*string*).
