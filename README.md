# 🎬 Booking Management System – UNA Film

**Booking Management System – UNA Film** je interna desktop aplikacija razvijena s ciljem digitalizacije i automatizacije administrativnih procesa u distributivnom odjelu kompanije **UNA Film d.o.o.**  
Aplikacija u potpunosti zamjenjuje dosadašnji rad u Excel tabelama i e-mail evidencijama te omogućava centralizovano upravljanje filmovima, kino partnerima i terminima prikazivanja.

> 🔒 Sistem je namijenjen isključivo internom korištenju unutar UNA Filma.

---

## 🧩 Osnovna ideja sistema

Kako partnerska kina sarađuju sa više distributera, korištenje posebne aplikacije za svakog dobavljača bilo bi nepraktično.  
Zbog toga se komunikacija prema partnerima i dalje odvija putem e-maila, dok se ova aplikacija koristi **interno** za:
- evidenciju filmova i partnera  
- planiranje i praćenje booking termina  
- kalendarski pregled prikazivanja  
- generisanje PDF/Excel izvještaja za administraciju i računovodstvo  

---

## 🛠️ Tehnologije

- **Programski jezik:** Java (JDK 17+)  
- **GUI:** JavaFX (FXML + CSS)  
- **Baza podataka:** MySQL (alternativno SQLite za demo)  
- **Arhitektura:** MVC (Model–View–Controller)  
- **PDF / Excel eksport:** iText / Apache PDFBox / Apache POI  
- **Kontrola verzije:** Git & GitHub  

---

## 📊 Funkcionalni moduli

### 📌 Dashboard
<img width="1200" height="779" alt="image" src="https://github.com/user-attachments/assets/6d6bbbb8-8522-437e-8825-11d78f7cb3e2" />

Centralni pregled stanja sistema sa osnovnim statistikama:
- broj filmova, partnera i booking termina  
- brzi uvid u aktivne i nadolazeće projekcije  
- grafički prikaz ključnih podataka iz baze  

---

### 🎟️ Booking
<img width="1198" height="779" alt="image" src="https://github.com/user-attachments/assets/1dd44e99-4baa-4854-a2ad-9dcb4563c608" />

Modul za kreiranje i upravljanje booking terminima:
- unos filma, partnera i perioda prikazivanja  
- validacija datuma i podataka prije snimanja  
- evidencija statusa (aktivno, završeno, izmijenjeno)  


---

### 🏢 Partneri
<img width="1199" height="776" alt="image" src="https://github.com/user-attachments/assets/86e1ce8e-d399-46e7-8c41-4a577a15f880" />
 
Baza kino partnera:
- naziv kina, grad, adresa  
- kontakt osoba, email i telefon  
- interna evidencija saradnje i napomena  
- brza pretraga i filtriranje partnera  

---

### 🎞️ Filmovi
<img width="1200" height="780" alt="image" src="https://github.com/user-attachments/assets/fc51a4f9-4ab9-44db-9f28-32513f7f28c9" />
 
Centralizovana baza filmova:
- naziv i originalni naziv  
- žanr, trajanje, godina izlaska  
- period distribucije i status  
- administracija kataloga filmova UNA Filma  

---

### 📅 Booking kalendar
<img width="1201" height="778" alt="image" src="https://github.com/user-attachments/assets/d35203f9-b44f-4ce8-aea1-a9ae48ebccf7" />
 
Vizuelni kalendarski prikaz svih termina:
- pregled projekcija po danima i mjesecima  
- filtriranje po filmu ili partneru  
- lakše planiranje i izbjegavanje preklapanja termina  

---

### ⚙️ Postavke
<img width="1199" height="777" alt="image" src="https://github.com/user-attachments/assets/af7234b0-1b65-43f8-a503-30cbc4b51376" />

Administrativne i korisničke postavke:
- upravljanje korisničkim nalozima i ulogama  
- podešavanje teme (Light / Dark mode)  
- osnovne sistemske konfiguracije  
- sigurnosne i validacijske opcije  

---

## 🔐 Sigurnost i pouzdanost

- autentifikacija i autorizacija korisnika  
- hashiranje lozinki  
- validacija svih unosa prije upisa u bazu  
- stabilan rad bez gubitka podataka  
- mogućnost backup-a baze  

---

## 📦 Status projekta

✔️ Projekat razvijen kao **akademski i praktični softverski sistem**  
✔️ Korišten u svrhu demonstracije modernog desktop rješenja  
✔️ Spreman za prezentaciju i dalju nadogradnju  
