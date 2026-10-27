# Fizjoterapeuci
# przychodnia - program do obsługi pacjentów i wizyt

aplikacja desktopowa dla przychodni. pozwala prowadzić listę pacjentów i lekarzy, umawiać wizyty i sprawdzać terminarz. dzięki niej nie trzeba pisać wszystkiego na kartkach.

## co robi program

### pacjenci
- dodaje nowego pacjenta (imię, nazwisko, pesel, data urodzenia, telefon)
- pozwala edytować i usuwać dane pacjenta
- wyświetla wszystkich pacjentów w tabeli
- wyszukuje pacjenta po nazwisku lub peselu

### lekarze
- dodaje nowego lekarza (imię, nazwisko, specjalizacja, gabinet)
- pozwala edytować i usuwać lekarzy
- wyświetla listę lekarzy w tabeli

### wizyty
- umawia pacjenta do wybranego lekarza na konkretny dzień i godzinę
- sprawdza, czy termin jest wolny (lekarz nie może mieć dwóch wizyt o tej samej godzinie)
- pozwala zmienić termin wizyty albo ją odwołać
- pozwala dopisać krótką notatkę do wizyty

### terminarz
- pokazuje wizyty z wybranego dnia
- pozwala wybrać lekarza i zobaczyć tylko jego wizyty
- widać, które godziny są zajęte, a które wolne

## sprawdzanie danych

program pilnuje, żeby użytkownik nie wpisał głupot:
- imię i nazwisko nie mogą być puste
- pesel musi mieć 11 cyfr
- telefon może mieć tylko cyfry
- nie da się zapisać wizyty w zajętym terminie
- przed usunięciem pacjenta lub lekarza program pyta, czy na pewno

## jak się używa (przykład)

1. pacjent dzwoni i chce się umówić do lekarza.
2. recepcjonistka znajduje go na liście pacjentów (albo dodaje nowego).
3. w oknie wizyty wybiera pacjenta, lekarza, datę i godzinę.
4. klika "zapisz".
5. wizyta pojawia się w terminarzu.
