# Biblioteka

> Aplikacja webowa umożliwiająca przeglądanie katalogu książek, ich wypożyczanie, rezerwowanie oraz zarządzanie wypożyczeniami.

---

## Autorzy

- Amelia Ledzińska
- Emilia Gzyl

---

## Cel aplikacji

Celem projektu jest stworzenie aplikacji umożliwiającej użytkownikom wygodne korzystanie z biblioteki. Aplikacja pozwoli na przeglądanie dostępnych książek, ich wypożyczanie i rezerwowanie, a także kontrolowanie terminów zwrotu.

---

## Planowane funkcje

### 1. Przeglądanie katalogu książek

- Wyświetlanie listy książek.
- Wyszukiwanie według tytułu i autora.
- Filtrowanie według kategorii i dostępności.

### 2. Wypożyczanie i rezerwowanie książek

- Możliwość wypożyczenia dostępnej książki na okres 2 tygodni.
- Możliwość zarezerwowania książki, która jest aktualnie niedostępna.
- Rezerwacja obowiązuje na kolejny dostępny termin wypożyczenia.

### 3. Zarządzanie wypożyczeniami

- Wyświetlanie listy aktualnie wypożyczonych książek.
- Informacja o terminach zwrotu.
- Możliwość przedłużenia wypożyczenia, jeżeli książka nie została zarezerwowana przez innego użytkownika.

### 4. Kontrola terminów i naliczanie kar

- Blokowanie możliwości kolejnych wypożyczeń i rezerwacji w przypadku przetrzymania książki.
- Naliczanie kar za przekroczenie terminu zwrotu.

---

## Wykorzystane technologie

| Warstwa | Technologia |
| **Frontend** | React + Vite |
| **Backend** | Node.js + Express |
| **Baza danych** | MongoDB + Mongoose |

---

## Struktura bazy danych

Aplikacja będzie korzystać z następujących kolekcji:

| Kolekcja | Opis |
| `users` | Dane użytkowników biblioteki. |
| `books` | Informacje o książkach, m.in. tytuł, autor, kategoria i dostępność. |
| `reservations` | Informacje o wypożyczeniach i rezerwacjach, w tym daty rozpoczęcia i zakończenia. 