# CourseCatalog

Platformă web pentru cursuri și înscrieri. Aplicația afișează cursurile disponibile, arată în timp real câte locuri mai sunt libere și permite utilizatorilor să se înscrie. Administratorul gestionează cursurile și înscrierile.

Proiect realizat la disciplina **Programare multimedia**.
**Autor:** Latco Daria ·

## Stadiul proiectului

Acest repository conține **Tema 1**: structura aplicației, designul și paginile statice (HTML, CSS și Bootstrap). Se adaugă în etapele următoare: baza de date, validările JavaScript pentru formulare și operațiile CRUD complete.

## Ce rezolvă aplicația

Informațiile despre cursuri sunt de obicei împrăștiate, iar organizatorii nu știu mereu câte locuri au rămas. CourseCatalog adună totul într-un singur loc: cursuri cu detalii, locuri libere afișate vizual și înscriere online.

## Utilizatori

| Utilizator | Ce poate face |
|---|---|
| **Vizitator** | Vede catalogul, caută cursuri și citește detaliile lor |
| **Utilizator înregistrat** | Se înscrie la cursuri, își vede înscrierile și le poate anula |
| **Administrator** | Adaugă, modifică și șterge cursuri și gestionează înscrierile |

## Pagini

| Pagină | Fișier |
|---|---|
| Pagina principală | `index.html` |
| Catalog cursuri (cu filtre) | `courses.html` |
| Detalii curs | `course-details.html` |
| Autentificare și cont nou | `login.html` (`register.html` redirecționează către formularul de cont nou) |
| Înscrierile mele | `my-enrollments.html` |
| Administrare | `admin.html` |

## Module

- **Catalog cursuri**: afișare, căutare și filtrare
- **Conturi utilizatori**: înregistrare și autentificare
- **Înscrieri**: înscriere la cursuri și anulare
- **Locuri disponibile**: afișarea locurilor libere și ocupate
- **Administrare**: gestionarea cursurilor și a înscrierilor

## Design

- **Framework CSS:** Bootstrap 5.3 (design responsive pentru desktop și telefon)
- **Fonturi:** Playfair Display (titluri) și Poppins (text)
- **Paleta de culori:**

| Culoare | Cod | Folosire |
|---|---|---|
| Roz intens | `#D6336C` | butoane și accente |
| Roz pudră | `#F8C8DC` | fundaluri și borduri |
| Lavandă | `#B8A1E3` | detalii și hover |
| Crem | `#FFF5F7` | fundalul paginii |
| Mov închis | `#3D2C4D` | text |

Locurile libere sunt afișate prin 10 buline: cele pline reprezintă locurile ocupate.

## Tehnologii

- HTML5
- CSS3 (fișier extern `css/style.css`)
- Bootstrap 5.3 și Bootstrap Icons
- Google Fonts
- JavaScript (afișarea cursului ales în pagina de detalii)

## Structura proiectului

```
CourseCatalog/
├── index.html
├── courses.html
├── course-details.html
├── login.html
├── register.html
├── my-enrollments.html
├── admin.html
├── README.md
└── css/
    └── style.css
```

## Instrucțiuni de rulare

1. Descarcă proiectul: pe GitHub apasă **Code → Download ZIP** și dezarhivează, sau clonează repository-ul:

   ```
   git clone https://github.com/darialatco/CourseCatalog.git
   ```

2. Deschide fișierul `index.html` într-un browser (Chrome, Edge sau Firefox).
3. Navighează între pagini folosind meniul de sus.

Nu este nevoie de instalare sau de server. Ai nevoie de conexiune la internet, pentru că Bootstrap, iconițele și fonturile se încarcă de pe CDN.

## Autor

Latco Daria, Master TM