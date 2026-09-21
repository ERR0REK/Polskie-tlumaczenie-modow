# Changelog

Wszystkie istotne zmiany w tej paczce są dokumentowane w tym pliku.
Format oparty na [Keep a Changelog](https://keepachangelog.com/pl/1.1.0/), wersjonowanie zgodne z [SemVer](https://semver.org/lang/pl/).

## [1.0.0] - Niewydane

Pierwsze publiczne wydanie paczki dla społeczności.

### Dodane

- Pełne polskie tłumaczenia dla **272 modów** do Minecraft **1.21.1** — od Create i całej rodziny addonów, przez Mekanism, Immersive Engineering, Farmer's Delight, Biomes O' Plenty, po JEI, Jade, FTB i Xaero's.
- Pokrycie weryfikowane **klucz po kluczu** względem źródeł `en_us.json` — zero brakujących kluczy.
- Jednolita terminologia na całą paczkę: nazwy maszyn, materiałów, tooltipy, ekrany konfiguracji, kategorie JEI i osiągnięcia trzymają wspólny słownik.
- Tłumaczenia zgodne z oficjalną polską terminologią Minecrafta tam, gdzie istnieje (*Netheryt*, *Fortuna*, *Zaklęcie ostateczne*...).
- Klimat Create: addony Create tłumaczone w konwencji znanej z polskiej społeczności Create, żeby poradniki i filmy dalej miały sens.
- Przetłumaczone ekrany konfiguracji (Mekanism, Supplementaries, JEI i inne), nie tylko nazwy bloków i przedmiotów.
- **Licencja CC BY-SA 4.0** — paczka jest udostępniona na licencji Creative Commons Attribution-ShareAlike 4.0: pełny tekst w pliku `LICENSE`, sekcja licencji w README oraz w opisie Modrinth.

### Naprawione

- **46 niezgodności placeholderów** (`%s` / `%1$s`) — m.in. ryzyko crashu przy nadmiarowych placeholderach i puste wartości przy utraconych (przełączanie shaderów, energia Mekanism, modyfikatory beczek Sophisticated Storage).
- Usunięte **hybrydy polsko-angielskie** („Elite Fabryka", „CNC Rolling Młyn", „Szansa butów"...) — ponad 290 poprawek, w tym cała rodzina Mekanism (837 kluczy), Create Big Cannons, chipped, Sophisticated Storage i Supplementaries.
- Poprawki gramatyki i rodzajów („Żelazny Beczka" → *Żelazna beczka*), nazw zaklęć i oficjalnych nazw vanilla (*Szczęścia Morza*, *Skrzywiony grzyb*).
- Ujednolicenie „Diesel" → *Olej Napędowy* w całym modpacku (TFMG, Create Diesel Generators, Oritech).

### Techniczne

- Wszystkie pliki JSON poprawne składniowo (267/267) i bez BOM.
- Naprawiona wielkość liter w `assets/securitycraft` — Minecraft ładuje zasoby z rozróżnianiem liter, nawet na Windows.
- Placeholdery zachowane 1:1 z oryginałem w każdym przetłumaczonym stringu.

[1.0.0]: https://github.com/ERR0REK/Polskie-tlumaczenie-modow/releases/tag/v1.0.0
