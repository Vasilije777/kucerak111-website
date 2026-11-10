# Kućerak 111 - Holiday House Promotional Website

Zvanični promotivni i informativni veb-sajt za turistički smeštaj **"Kućerak 111"**, smešten u Banji Vrdnik na obroncima Fruške gore. Projekat je razvijen kao samostalno rešenje iz realnog sveta sa ciljem da posetiocima predstavi smeštajne kapacitete, prateće sadržaje i omogući direktnu rezervaciju.

## 🌟 Ključne karakteristike projekta

* **Moderan UI/UX dizajn:** Izrađen uz pomoć modernog *Tailwind CSS* okvira sa prilagođenom paletom boja (bež, maslinasti i zemljani tonovi) prilagođenom prirodi i planinskom ambijentu.
* **Dvojezična podrška (Srpski / Engleski):** Potpuno prilagođen domaći i strani turisti (stranice `index.html` i `en.html`).
* **Interaktivne komponente i galerije:**
  * **Modali (Popup prozori)** za detaljan pregled specifičnosti svakog apartmana (Plavi, Zeleni i Žuti) sa integrisanim sistemom za prebacivanje slika.
  * **Automatski karusel (Slider)** sa prilagođenom logikom klizanja i interaktivna *Lightbox* galerija za prikaz eksterijera i dvorišta.
* **Sistem za rezervacije i upite:**
  * Integrisan servis **Web3Forms** za direktan prijem upita u inbox bez potrebe za sopstvenim bekendom.
  * **Klijentska validacija datuma i telefona:** Onemogućavanje izbora datuma u prošlosti, automatsko prilagođavanje minimalnog datuma odjave i dinamička provera formata broja telefona.
  * **Zaštita od spama (Honeypot) i Rate Limiting:** Ugrađena zaštita od botova i vremensko ograničenje (5 minuta) između uzastopnih slanja upita kako bi se sprečile zloupotrebe.
* **Interaktivna mapa:** Ugrađena Google Maps lokacija (Vojvođanske brigade 93, Vrdnik).

---

## 🛠️ Korišćene tehnologije

* **HTML5** & **JavaScript (ES6+)** – Struktura i klijentska logika (upravljanje modalima, sliderima, validacijama i lokalnom memorijom).
* **Tailwind CSS** (kroz CDN) – Dizajn korisničkog interfejsa i respozivnost (Mobile-first pristup).
* **FontAwesome (v6.4.0)** – Ikonice za vizuelno obogaćivanje interfejsa.
* **Google Fonts** (*Plus Jakarta Sans* & *Playfair Display*) – Tipografija i vizuelni identitet brenda.
* **Web3Forms API** – Sigurno prosleđivanje mejl upita sa kontakt forme.
