Car Maintenance Log (Nikola Servisna Knjižica) je Android aplikacija namenjena vlasnicima vozila za efikasno upravljanje podacima o njihovim automobilima. Aplikacija omogućava digitalno vođenje evidencije o vozilima, servisima automobila radi lakšeg praćenja održavanja.

Lista funkcionalnosti

Obavezne funkcionalnosti (Must-have):
Autentifikacija: Početni ekran sa validacijom email-a i lozinke pre pristupa garaži.  
Garaža vozila: Pregled liste svih unetih automobila (marka, model, godište).  
Detaljna evidencija vozila: Unos specifičnih podataka kao što su broj šasije, kubikaža, tip goriva i pređena kilometraža.  
Servisni dnevnik: Povezivanje svakog vozila sa istorijom servisa preko ID-ja (1:N relacija).  
Lokalna baza (Room): Svi podaci se trajno čuvaju na uređaju u SQLite bazi.  
Empty/Error State: Prikaz jasnih poruka korisniku u slučaju praznih lista ili pogrešnog unosa.

Tehnologije

Jezik: Java
Arhitektura: Slojeviti dizajn (UI -> DAO -> Room Database)  
Baza podataka: Room Persistence Library (Entiteti: Automobil, Service)  
UI Komponente: Material Design 3, EdgeToEdge, ListView sa ArrayAdapter-om  
Threading: Manual Threads i runOnUiThread za asinhronu obradu podataka.

Kako se pokreće

Kloniranje: Klonirajte repozitorijum sa GitHuba.
Android Studio: Otvorite projekat u Android Studiju.  
Gradle: Sačekajte sinhronizaciju Gradle-a.  
Instalacija: Pokrenite aplikaciju na emulatoru ili fizičkom uređaju.

Test podaci

Demo vozilo: Audi A4, 2022. godište, Dizel, 2000 ccm.
Demo servis: Mali servis, Datum: 01.05.2026, KM: 150.000.
Validacija: Pokušajte da unesete automobil bez godišta ili marke ili unesite servis bez datuma.

Poznati problemi

Baza podataka je isključivo lokalna; nema sinhronizacije u oblaku (Cloud).

Autor

Ime i prezime: Nikola Živković

Broj indeksa: 1B1/0003/23

Datum: Maj, 2026.



