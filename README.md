
# Test de verificare – GitHub

---

### 1. Ce este un depozit și ce conține în plus față de un folder obișnuit de pe calculator?

Un depozit (repository) este un spațiu în care se păstrează fișierele unui proiect. În plus față de un folder obișnuit, acesta păstrează istoricul modificărilor prin commit-uri.

### 2. Ce este un commit? Ce informații înregistrează GitHub la fiecare commit?

Un commit este o salvare a modificărilor făcute într-un proiect. Git înregistrează modificările, mesajul commit-ului, autorul, data și ora salvării.

### 3. Care sunt regulile GitHub pentru parolă și pentru numele de utilizator?

Parola trebuie să respecte cerințele de securitate GitHub și să fie greu de ghicit.

Numele de utilizator poate conține litere, cifre și cratime (-), dar nu spații. Nu poate începe sau termina cu o cratimă și nu poate conține cratime consecutive.

### 4. Care dintre numele de utilizator sunt acceptate de GitHub?

- **ana-ionescu** – acceptat, deoarece conține litere și o cratimă între cuvinte.
- **-ana-** – neacceptat, deoarece începe și se termină cu o cratimă.
- **ana ionescu** – neacceptat, deoarece conține un spațiu.
- **ana_ionescu** – neacceptat, deoarece caracterul underscore nu este permis.

### 5. Ce se face pe calculatorul din laborator la sfârșitul orei și de ce?

Se face commit pentru ultimele modificări și se verifică dacă fișierele au fost încărcate pe GitHub, pentru a păstra munca realizată și a putea continua la ora următoare.

### 6. Prin ce diferă un depozit Public de unul Private? Care se alege pentru portofoliu și de ce?

**Public:** poate fi văzut de oricine.

**Private:** poate fi accesat doar de proprietar și de persoanele autorizate.

Pentru portofoliu se alege un depozit Public, pentru ca profesorii și alte persoane să poată vedea proiectele.

### 7. Se rescriu corect numele: Temă 2 Pliant (folder), Pliant FINAL.PDF (fișier).

**Folder:** `tema-02-pliant`

**Fișier:** `pliant-final.pdf`

### 8. Care sunt limitele la încărcarea din browser?

Prin interfața web GitHub se pot încărca fișiere de maximum **25 MiB** fiecare, în limita a **100 de fișiere odată**.

### 9. Afișul a fost corectat. Cum se încarcă varianta nouă și ce se întâmplă cu cea veche?

Se încarcă fișierul corectat cu același nume și în același folder, apoi se face commit.

Varianta veche este înlocuită în versiunea actuală, dar poate fi recuperată din istoricul commit-urilor.

### 10. Se scrie un mesaj de commit potrivit pentru înlocuirea fotografiei de pe fața pliantului de la tema 2.

**Înlocuire fotografie față pliant tema 2**

### 11. Utilizatorul maria-stan are depozitul portofoliu-media, cu fișierul pliant.pdf în folderul tema-02-pliant. Se scriu adresele.

**Adresa depozitului:**

https://github.com/maria-stan/portofoliu-media

**Adresa site-ului:**

https://maria-stan.github.io/portofoliu-media/

**Adresa fișierului pe site:**

https://maria-stan.github.io/portofoliu-media/tema-02-pliant/pliant.pdf

Adresele site-ului funcționează după activarea GitHub Pages și publicarea fișierelor.

### 12. Care sunt pașii de activare a GitHub Pages? Ce fișier este prima pagină a site-ului?

1. Se intră în depozitul GitHub.
2. Se deschide **Settings**.
3. Se selectează **Pages**.
4. La Build and deployment se alege **Deploy from a branch**.
5. Se selectează ramura **main**.
6. Se alege folderul **/ (root)**.
7. Se apasă **Save**.
8. Se așteaptă publicarea site-ului.

Prima pagină a site-ului este, de regulă, fișierul **index.html**.

### 13. Corectarea unui fragment HTML

Fișierele din depozit sunt:

- `tema-02-pliant/pliant.pdf`
- `tema-02-pliant/pliant-fata.png`

Un exemplu de cod HTML corect este:

    <a href="tema-02-pliant/pliant.pdf">
      Deschide pliantul PDF
    </a>

    <img src="tema-02-pliant/pliant-fata.png"
         alt="Fața pliantului">

Pentru identificarea exactă a celor patru greșeli este necesar fragmentul original din exercițiu.

