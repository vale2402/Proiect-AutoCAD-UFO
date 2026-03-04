# Proiect AutoCAD: Obiect Zburător Neidentificat (OZN) 🛸

Acest repository conține proiectul realizat pentru materia Grafică Asistată de Calculator din cadrul Facultății de Matematică și Informatică (Universitatea din București, specializarea Calculatoare și Tehnologia Informației).

Proiectul constă în proiectarea și modelarea detaliată a unui OZN, având ca sursă de inspirație designul jucăriei educaționale Levenhuk LabZZ SP50 UFO Planetarium. Scopul a fost îmbinarea pasiunii pentru astronomie și filmele SF cu abilitățile tehnice de modelare 2D și 3D.

## 📂 Structura Repository-ului

Proiectul este organizat logic, separând etapele de schițare de cele de modelare tridimensională:

* **`Schite 2D/`**
  Aici se regăsesc desenele tehnice și vederile de bază (ortogonale și secțiuni) necesare pentru a construi piesele.
  * Vederi generale: `Vedere de sus.dwg`, `Vedere de jos.dwg`, `Vedere laterala.dwg`.
  * Componente: `Detaliul 1 2D.dwg`, `Detaliul 2 2D.dwg`, `Detaliul 3 2D.dwg`, `LED 2D.dwg`, `Picioare pliante 2D.dwg`, `Suport interior 2D.dwg`.

* **`Modele 3D/`**
  Conține componentele individuale ridicate în 3D folosind comenzi precum *Extrude*, *Revolve* sau *Presspull*.
  * Piese: `Carcasă 3D.dwg`, `Detaliul 1 3D.dwg`, `Detaliul 2 3D.dwg`, `Detaliul 3 3D.dwg`, `LED-uri 3D.dwg`, `Picior pliant 3D.dwg`, `Suport interior 3D.dwg`.

* **Fișiere Principale (Root)**
  * 🪐 **`Produs final UFO.dwg`**: Fișierul complet ce conține asamblarea tuturor componentelor 3D.
  * 📸 **`Produs final UFO render.png`**: O imagine randată a modelului 3D final, ilustrând detaliile carcasei, LED-urile și picioarele de sprijin.
  * 📄 **`Proiect_Autocad_OZN.docx`**: Documentația oficială a proiectului, incluzând istoricul, motivația, setarea spațiului de lucru, definirea layerelor și pașii exacți de implementare.

## 🛠️ Detalii Tehnice

* **Software utilizat:** Autodesk AutoCAD 2025.
* **Compatibilitate:** Toate fișierele `.dwg` au fost salvate în formatul AutoCAD 2018 pentru a asigura o compatibilitate cât mai largă.
* **Unități de măsură:** Centimetri (scara 1:1).
* **Organizare:** Proiectul folosește 15 layere distincte (ex: *Carcasa superioara*, *LED*, *Picior pliant*, *Sfera centrala*) pentru a izola și gestiona ușor elementele vizuale.
