# Ataskaita apie kursinį darbą tema: Flight ticket reservation management system

## Įžanga
### Kas yra jūsų programa?
Mano programa yra skirta rezervuoti skrydžio bilietus.

### Kaip paleisti programą?
Paleisti programą reikėtų Python aplinkoje. Rekomenduotina per Google Colab.

### Kaip naudotis programa?
1. Paspaudus vykdyti programą, po ja atsiras 2 langeliai.
2. Paspaudus ant jų, reikia išsirinkti norimus išvykimo ir atvykimo miestus.
3. Tuomet paspauskite mygtuką **"Pasirinkti"**.
4. Atsiradusiuose langeliuose pasirinkite išvykimo datą, laiką ir įrašykite savo vardą.
5. Patikrinkite išvestą informaciją ir paspauskite mygtuką **"REZERVUOTI"**.
6. Mygtuku **"Peržiūrėti bilietus"** galite peržiūrėti jau rezervuotus bilietus.
7. Mygtuku **"Rezervuoti naują"** galite rezervuoti dar vieną bilietą.

## Analizė

### Abstrakcija
Programa naudoja abstrakčius metodus "Viskas" klasėje.

### Paveldėjimas
Programa naudoja paveldėjimą "Viskas2" klasėje ir leidžia šiai klasei naudoti metodus iš "Viskas" klasės.

### Enkapsuliacija
Programa naudoja enkapsuliaciją "God" klasėje ir užtikrina, kad "__tiket" kintamasis nebūtų tiesiogiai pasiekiamas už klasės ribų.

### Singletonas
Programa naudoja singletoną "singleton" metode ir užtikrina, kad "God" klasė turėtų tik vieną egzempliorių.

### Dekoratorius
Programa naudoja dekoratorių "God" klasei tam, kad pridėtų naują funkcionalumą nekeičiant klasės struktūros.

### Skaitymas iš failo ir rašymas į failą
"God" klasėje metodai, tokie kaip "add_city", įrašo duomenis į JSON failą. Metodai, tokie kaip "load_city", nuskaito duomenis iš failo.

### Unittest
Programa turi unit testus "TestFlightManager" klasėje. Tam, kad paleisti juos, reikia paskutinėje eilutėje ištrinti "#" ženklą ir paleisti programą. Šis testas patikrins {add_city, load_city, add_tiket, load_tiket, skaiciujaatstuma} metodų veikimą.

## Rezultatai ir Santrauka

### Rezultatai
Programa sėkmingai įgyvendina skrydžių bilietų rezervavimo sistemą.
Įgyvendinant programa susidurta su iššūkiais, tokiomis kaip datos ir laiko validavimas bei polimorfizmo užtikrinimas.
Testavimas buvo svarbus siekiant užtikrinti atstumo skaičiavimų tikslumą ir tinkamą duomenų nuskaitymo/įrašymo funkcionalumą.

### Pagrindinės išvados ir rezultatai
Darbo metu pavyko sukurti veikiantį skrydžių bilietų rezervavimo valdymo sistemą.
Šio darbo rezultatas yra Python programa, leidžianti vartotojams užsisakyti ir peržiūrėti skrydžių bilietus, užtikrinant duomenų enkapsuliaciją.
Ateities perspektyvos apima pažangesnių funkcijų, tokių kaip realaus laiko skrydžio būklės atnaujinimai, vartotojų autentifikacija pridėjimą.

### Galimi praplėtimai
Programą galima praplėsti įdiegiant vartotojų autentifikacijos sistemą, kad būtų galima valdyti vartotojų paskyras ir rezervacijų istoriją.
Programą būtų galima patobulinti pridėjus palaikymą įvairioms kalboms ir valiutoms, taip ją padarant prieinamesnę.
Pridėjimas realaus laiko atnaujinimus apie skrydžių būklę, vėlavimus ir atšaukimus, žymiai pagerintų vartotojų patirtį.
