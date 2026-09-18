# 🚗 Beberam Concept — Platformă Web Parc Auto

Aplicație web completă pentru prezentarea și gestionarea stocului unui parc auto second-hand din Pitești. Proiectul include un catalog public interactiv cu filtrări în timp real și un panou de administrare securizat pentru gestionarea anunțurilor.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

---

## 🌟 Ce știe să facă aplicația

### 🚘 Catalog Public (`index.html` & `detalii.html`)
* **Filtrare dinamică multi-criteriu:** Filtrare instantă după marcă, model, tip combustibil (Benzină, Diesel, GPL), an de fabricație și capacitate cilindrică.
* **Sistem de Favorite:** Salvarea mașinilor preferate direct în `localStorage` fără a necesita cont de utilizator.
* **Galerie media interactivă:** Carusel foto cu suport pentru fullscreen zoom (drag/pinch) și player video YouTube integrat automat.
* **Măsurare conversii:** Contorizare unică a vizualizărilor și a click-urilor pe numărul de telefon.

### 🔒 Panou Admin Securizat (`admin.html`)
* **Autentificare cu cod:** Acces restricționat direct în interfață.
* **CRUD Complet:** Adăugare, editare și ștergere anunțuri cu sincronizare în Supabase.
* **Compresie poze direct în browser:** Redimensionare și optimizare automată a imaginilor încărcate (HTML5 Canvas) pentru încărcare rapidă.
* **Reordonare Drag & Drop:** Modificare ordine afișare mașini în catalog folosind `SortableJS`.
* **Analitice în timp real:** Vizualizare număr de vizionări, apăsări de telefon și salvări la favorite pentru fiecare mașină.
* **Parser Video YouTube:** Extragere automată a ID-ului din orice format de link YouTube (standard, shorts, share) și conversie în player interactiv.

---

## 🛠️ Stack Tehnic

* **Frontend:** HTML5 Semantic, CSS3 (Flexbox & CSS Grid responsiv), Vanilla JavaScript (ES6+ Async/Await).
* **Database & BaaS:** [Supabase](https://supabase.com/) (PostgreSQL client-side API).
* **Librării terțe:** 
  * [SortableJS](https://sortablejs.github.io/Sortable/) — Reordonare elemente prin Drag & Drop.
  * [FontAwesome 6](https://fontawesome.com/) — Iconițe UI și Social Media.

---

## 📂 Structura Proiectului

```text
├── index.html     # Pagina principală (Catalog + Filtre)
├── detalii.html   # Pagina individuală a fiecărui vehicul
├── admin.html     # Panoul de administrare & gestiune stoc
└── README.md      # Documentația proiectului
