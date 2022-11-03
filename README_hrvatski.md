# BrailleZephyr ekstenzija za hrvatski

- Kako bi se omogucilo pisanje hrvatske brajice napravljen je novi font u Font Forge programu.
- Prevedeno je korisničko sučelje na hrvatski jezik.

## Legenda - kako se pojedini znakovi biti vidljivi u desnom prozoru
- predznak za broj: #
- predznak za veliko slovo: $
- predznak za više velikih slova: znak funte
- zadnji znak u %: %

## Kratke upute
- Kako bi se koristilo hrvatsko znakovlje potrebno je ici u Pregled/Braille font i odabrati "BrailleZephyr_6" font.
- Najjednostavnije je pokrenuti program tako da se otvori Command Line, smjesti se u pocetni direktorij projekta i pozove se naredba:
gradlew allJars
- Zatim se builda pozivom:
gradlew build
- i pokrene:
gradlew run

- Jednom buildani program moguce je distribuirati bez ponovnog buildanja.
- Kad se program builda u build/distributions nalazi se .zip datoteka koja se može slati s PC-ja na PC.
- Kad se extract-a u /bin direktoriju nalazi se .bat skripta koja se pokrece na Windows OS-u i koja pokrece program.

- Done by: Petra Šalković and Karlo Rataić
