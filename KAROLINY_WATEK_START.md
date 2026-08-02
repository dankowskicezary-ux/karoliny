# Karoliny - kontekst do osobnego watku

Projekt: osobna aplikacja PWA `Karoliny`, niezalezna od planu keto.

Folder lokalny:
`C:\Users\Admin\Documents\Codex\2026-06-21\b\outputs\karoliny-plan-app`

Glowne pliki:
- `index.html`
- `app.js`
- `styles.css`
- `sw.js`
- `manifest.webmanifest`
- `README.md`

Aktualna wersja aplikacji:
`Karoliny v3`

Glowne wytyczne:
- Insulinoopornosc.
- Malo weglowodanow.
- Niski ladunek glikemiczny.
- Bez cukru.
- Kalorie maja zostac edytowalne przez uzytkowniczke.
- Domyslne cele: 1600 kcal, 120 g bialka, 90 g wegli, 75 g tluszczu.
- Bez kawy i bez Nootri.

Wykluczenia:
- mleko
- jogurt naturalny
- kefir
- skyr
- wiekszosc nabialu
- brukselka
- owsianki
- owoce cytrusowe
- tluste miesa
- pieczony kalafior

Dozwolone z nabialu:
- serek homogenizowany bez cukru
- ser bialy / twarog

Wazne zachowania aplikacji:
- Uzytkowniczka moze ustawic limit kcal.
- Makra sa ustawione pod niski ladunek glikemiczny.
- Aplikacja ma jadlospis, wode, liste zakupow, wyniki, wlasne posilki i przepisy z dodatkami.
- Sekcja kawy/Nootri zostala usunieta.
- Panel wody i przypomnienia wody zostaly.
- Aktywna baza po filtrze: 31 dan i 196 produktow.

Sprawdzone:
- `node --check app.js` przechodzi.
- Filtr wykluczen nie pokazuje zakazanych produktow w aktywnej bazie.

Zrodla uzyte do wytycznych:
- NIDDK: insulin resistance / prediabetes
- Diabetes UK: glycaemic index
- Linus Pauling Institute: glycemic index/load
- ADA: nutrition therapy consensus

Prosba do nowego watku:
Kontynuuj prace tylko nad aplikacja `Karoliny` w folderze podanym wyzej. Nie mieszaj zmian z aplikacja keto.
