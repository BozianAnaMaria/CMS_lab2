# CMS_lab2


## Lucrarea de laborator nr. 3. Dezvoltarea unei teme WordPress simple
###Pasul 1. Pregătirea mediului
- În instalarea locală WordPress, accesează folderul wp-content/themes.
- Creează un director pentru tema ta, de exemplu usm-theme.

- Activează modul de depanare în wp-config.php, adăugând define('WP_DEBUG', true);.


### Pasul 2. Crearea fișierelor obligatorii ale temei
- În folderul temei, creează fișierul style.css cu metadatele temei.
- După metadate, poți adăuga reguli CSS de bază.
- Creează fișierul index.php – șablonul principal al temei. Pentru început, adaugă o structură HTML de bază.


### Pasul 3. Componente comune ale șabloanelor
- Creează fișierul header.php și mută acolo codul antetului site-ului (până la începutul conținutului principal).
- Creează fișierul footer.php și mută acolo codul subsolului site-ului (după conținutul principal).
- În index.php, include header.php și footer.php folosind funcțiile get_header() și get_footer().
- Pe pagina principală, afișează o listă cu ultimele 5 postări folosind bucla WordPress.


### Pasul 4. Fișierul de funcții
- Creează fișierul functions.php în directorul temei.
- În functions.php, adaugă o funcție pentru încărcarea stilurilor temei folosind wp_enqueue_style().


### Pasul 5. Șabloane suplimentare
- Creează fișierul single.php pentru afișarea unei postări individuale.
- Creează fișierul page.php pentru afișarea paginilor.
- Creează fișierul sidebar.php pentru bara laterală și include-l în șabloanele relevante cu get_sidebar().
- Creează fișierul comments.php pentru afișarea comentariilor și include-l în single.php și page.php.
- Creează fișierul archive.php pentru afișarea arhivelor postărilor.


### Pasul 6. Stilizarea temei
- Adaugă stiluri pentru elementele principale ale temei (antet, subsol, conținut, bara laterală).


### Pasul 7. Captura de ecran a temei
- Adaugă în folderul temei fișierul screenshot.png – o imagine de previzualizare a temei (dimensiune 1200x900px).


### Pasul 8. Activarea temei
- În panoul de administrare WordPress, accesează secțiunea Appearance → Themes.
- Găsește tema ta și activeaz-o.
- Verifică modul în care site-ul este afișat cu tema ta.


### Întrebări de control
- Care sunt cele două fișiere obligatorii pentru orice temă WordPress?
- Cum se includ părțile comune ale șabloanelor (header, footer, sidebar)?
- Care este diferența dintre index.php, single.php și page.php?
- Care este rolul fișierului functions.php într-o temă?
