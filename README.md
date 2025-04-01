# SFML Aiming Game

Ett enkelt arkadliknande "aim trainer"-spel byggt med C++ och SFML. Målet är att klicka på fallande fiender innan de når botten av skärmen — och samla så många poäng som möjligt!

## Gameplay

- Klicka på rektanglar ("enemies") i olika storlekar och färger.
- Varje färg ger olika poäng.
- Missar du en fiende tappar du hälsa.
- Spelet avslutas när du har 0 i hälsa.

## Teknik

- Språk: C++
- Ramverk: [SFML (Simple and Fast Multimedia Library)](https://www.sfml-dev.org/)
- Funktioner:
  - Fönsterhantering och rendering
  - Musinteraktion och kollisionsdetektion
  - UI-text (poäng, hälsa)
  - Enkel "enemy spawning"-logik med timers
  - Objekt lagrade i `std::vector`
  - 
### Förutsättningar

- C++ kompilator (GCC eller MSVC)
- [SFML 2.5+](https://www.sfml-dev.org/download.php) installerat och korrekt länkat
