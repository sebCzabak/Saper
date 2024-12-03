# Saper - Gra w Konsoli

Prosta gra Saper napisana w C# z interfejsem konsoli. Gracz odkrywa pola na planszy, unikając bomb. Liczby na odkrytych polach wskazują liczbę bomb w sąsiednich polach.

---

## 🕹️ Funkcjonalności

- **Plansza 10x10:** Losowe rozmieszczenie bomb.
- **Obsługa gracza:** Odkrywanie pól na podstawie współrzędnych podanych przez gracza.
- **Logika gry:** Rozszerzanie pustych pól, liczba sąsiednich bomb, warunki wygranej i przegranej.
- **Czytelny interfejs:** Wyświetlanie planszy z numeracją wierszy i kolumn.

---

## 🚀 Jak zagrać?

1. Uruchom grę w swoim środowisku (np. Visual Studio).
2. Podaj współrzędne pola, które chcesz odkryć, w formacie:  
x y

yaml
Skopiuj kod
Przykład: `2 3` (kolumna 2, wiersz 3).
3. Odkrywaj kolejne pola, starając się unikać bomb.

### Cel gry
- Odkryj wszystkie pola bez bomb.
- Unikaj pól zawierających bomby.

---

## 🔧 Instalacja

1. **Sklonuj repozytorium:**
```bash
git clone [https://github.com/your-username/saper-game.git](https://github.com/sebCzabak/Saper) 
```
2. Otwórz projekt w IDE:
Użyj dowolnego środowiska obsługującego C# (np. Visual Studio).
3. Uruchom projekt:
Skompiluj kod i uruchom aplikację. 
