<div align="center">

<img src="https://github.com/user-attachments/assets/8d4a1d8b-f4db-4baf-99c8-6d4f39795ee4" alt="Fintech Nova Dashboard" width="100%" />

  <br />
  <br />

  # 🚀 Fintech Nova Dashboard
  
  **Futuristički bankarski interfejs dizajniran za napredno upravljanje ličnim finansijama.**

  <p>
    <a href="#-o-projektu">O Projektu</a> •
    <a href="#-ključne-funkcionalnosti">Funkcionalnosti</a> •
    <a href="#-tehnologije">Tehnologije</a> •
    <a href="#-kako-pokrenuti">Instalacija</a>
  </p>

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![Status](https://img.shields.io/badge/Status-Aktivan-success?style=for-the-badge)

</div>

---

## 💡 O Projektu

**Fintech Nova** je sveobuhvatno *frontend* rešenje koje simulira moderno bankarsko okruženje. Projekat je fokusiran na **vizuelizaciju podataka**, **sigurnosni monitoring** i **korisničko iskustvo (UX)**. Dashboard pruža pregled finansijskog stanja u realnom vremenu, analizu rizika i kursnu listu, sve upakovano u moderan "Dark Mode" dizajn sa neonskim akcentima.

Ovaj projekat demonstrira naprednu manipulaciju DOM-om, responzivni CSS (Grid/Flexbox) i interaktivne UI komponente bez upotrebe teških framework-a.

---

## 💎 Ključne Funkcionalnosti

### 🛡️ **Centar za Sigurnost (Security Intel)**
* **Analiza Rizika u Realnom Vremenu:** Vizuelni prikaz statusa sigurnosti putem dinamičkog kružnog dijagrama (trenutni nivo rizika: *32%*).
* **Detaljna Metrika:** Praćenje Autentifikacije (95%), Aktivnosti Računa (78%) i Enkripcije prometa.
* **Kontrola Postavki:** Interaktivni *toggle* prekidači za Biometriju, 2FA zaštitu i Notifikacije.

### 💳 **Finansijski Menadžment**
* **Smart Wallet:** Prikaz trenutnog salda (€2340.00) sa detaljima virtuelne kartice.
* **Kategorizacija Troškova:** Interaktivni izbor tipa transakcije (Kupovina, Hrana, Prijevoz, Edukacija, Putovanja).
* **Brze Akcije:** Prečice jednim klikom za Prenos novca, Zahtjeve i Plaćanje računa.

### 📊 **Analitika i Alati**
* **Kursna Lista:** Integrisana tabela za praćenje valuta (EUR, BAM, USD, GBP) sa automatskim preračunom.
* **Tok Potrošnje:** Grafički prikaz istorije transakcija kroz vreme.
* **AI Asistent:** Ugrađen *chat widget* za brzu podršku i navigaciju kroz aplikaciju.

---

## 🛠 Tehnologije

Projekat je izrađen koristeći čiste (*vanilla*) web tehnologije kako bi se osigurale maksimalne performanse i brzina učitavanja.

| Tehnologija | Primena |
| :--- | :--- |
| **HTML5** | Semantička struktura i organizacija elemenata. |
| **CSS3** | Napredno stilizovanje koristeći **Flexbox**, **Grid** i **CSS Varijable**. Implementiran *Glassmorphism* efekat i animacije. |
| **JavaScript (ES6)** | Logika za konverziju valuta, simulaciju grafikona, *toggle* stanja i filtriranje kategorija. |
| **SVG Icons** | Skalabilna vektorska grafika za oštar prikaz na svim ekranima. |

---

## 🎨 Dizajn Sistem

Interfejs prati **Cyberpunk / Neo-Fintech** estetiku:

* **Paleta Boja:** Tamna pozadina (`#0a0e17`) u kombinaciji sa Neonsko Plavom (`#00f2ff`) i Emerald Zelenom (`#00ff88`).
* **Tipografija:** Sans-serif fontovi optimizovani za čitljivost numeričkih podataka.
* **Vizuelna Hijerarhija:** Korišćenje kartica i sekcija za vođenje oka korisnika (F-pattern čitanje).
* **Dark Mode:** Ugrađen kao podrazumevana tema radi smanjenja zamora očiju.

---

## 🚀 Instalacija i Pokretanje

Da biste pokrenuli ovaj projekat lokalno, pratite sledeće korake:

1.  **Klonirajte repozitorijum**
    ```bash
    git clone [https://github.com/tvoj-username/fintech-nova.git](https://github.com/tvoj-username/fintech-nova.git)
    ```

2.  **Pozicionirajte se u folder**
    ```bash
    cd fintech-nova
    ```

3.  **Pokrenite aplikaciju**
    Jednostavno otvorite `index.html` fajl u bilo kojem modernom pretraživaču.
    *Preporuka: Koristite VS Code "Live Server" ekstenziju za najbolje iskustvo.*

---

## 📂 Struktura Projekta

```text
fintech-nova/
├── assets/
│   ├── images/          # Profilne slike, pozadine kartica
│   └── icons/           # SVG ikonice za kategorije
├── css/
│   ├── style.css        # Glavni stilovi
│   └── responsive.css   # Prilagođavanje za mobilne uređaje
├── js/
│   ├── main.js          # Glavna funkcionalnost
│   └── charts.js        # Logika za grafikone i vizuelizaciju
├── index.html           # Glavni layout dashboarda
└── README.md            # Dokumentacija projekta
