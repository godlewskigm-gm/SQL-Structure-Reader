# SQL Structure Reader

Free Windows (WPF) tool to explore Microsoft SQL Server database structure. **No license / activation required.**

> **Copyright / terms:** see [About.txt](./About.txt) — free to use; source code is not public; all rights reserved by **Maksym Goldevskyi**.

**Download (installer):** [SQL Structure Reader 3.1 — Releases](https://github.com/godlewskigm-gm/SQL-Structure-Reader/releases/latest)

Requirements: Windows 10/11 (x64). The published installer is **self-contained** (no separate .NET install needed in typical cases).

---

# SQL Structure Reader — przewodnik użytkownika (PL) / User Guide (EN)

---

## Polski

### Czym jest program

**SQL Structure Reader** (v3.1) to aplikacja desktopowa Windows (WPF) do eksploracji struktury Microsoft SQL Server: tabele, widoki, procedury, funkcje, relacje FK, porównanie baz, Query Lab (SELECT) oraz eksport.

Program jest całkowicie darmowy i **nie wymaga żadnej licencji** ani aktywacji.

### Cel

- szybko zobaczyć schemat bazy,
- porównać dwie bazy,
- uruchamiać bezpieczne zapytania SELECT,
- eksportować strukturę (JSON, TXT, HTML, DDL),
- pracować w trybie DEMO bez prawdziwego serwera.

### Jak uruchomić

1. Pobierz instalator z [Releases](https://github.com/godlewskigm-gm/SQL-Structure-Reader/releases/latest) i zainstaluj **albo** uruchom **SQLStructureReader.exe**.
2. Windows 10/11 x64. Wersja instalatora jest self-contained.

### Jak zacząć — krótki przepis

1. W panelu **Połączenie** podaj serwer SQL (Windows Auth lub login/hasło).
2. **Połącz / test** — pobierz listę baz, wybierz bazę.
3. **Odczytaj strukturę** — drzewo obiektów po lewej, szczegóły po środku.
4. Narzędzia: **SQL Query Lab**, **Diagram relacji**, **Porównaj bazy**.
5. Eksport: JSON / TXT / HTML / DDL.
6. **Motyw** jasny/ciemny oraz język **PL** / **EN** w sidebarze.
7. **O programie** — informacje o autorze oraz zakładka **Donate / Podziękowanie**.

### Przydatne funkcje

- Zapisane profile połączeń (hasła chronione DPAPI).
- Notatki do obiektów (lokalnie w `%LOCALAPPDATA%\SQL Structure Reader\`).
- Ostrzeżenia jakości schematu, mini-diagram relacji kolumn.

### Czego program nie robi

Query Lab jest ograniczony do zapytań SELECT — nie służy do zmian danych ani administracji serwerem. Nie zastępuje pełnych narzędzi typu SSMS przy złożonej administracji.

### Autor i zasady

Maksym Goldevskyi. Szczegóły praw autorskich: [About.txt](./About.txt).

---

## English

### What the program is

**SQL Structure Reader** (v3.1) is a Windows desktop app (WPF) for exploring Microsoft SQL Server structure: tables, views, procedures, functions, FK relationships, database compare, Query Lab (SELECT), and export.

The software is completely free and **does not require any license** or activation.

### Purpose

- quickly inspect a database schema,
- compare two databases,
- run safe SELECT queries,
- export structure (JSON, TXT, HTML, DDL),
- use DEMO mode without a real server.

### How to run it

1. Download the installer from [Releases](https://github.com/godlewskigm-gm/SQL-Structure-Reader/releases/latest) **or** run **SQLStructureReader.exe**.
2. Windows 10/11 x64. The installer build is self-contained.

### How to start — short recipe

1. In **Connection**, enter the SQL server (Windows Auth or SQL login/password).
2. **Connect / test** — load databases, pick one.
3. **Read schema** — object tree on the left, details in the center.
4. Tools: **SQL Query Lab**, **Relationship diagram**, **Compare databases**.
5. Export: JSON / TXT / HTML / DDL.
6. Light/dark **Theme** and **PL** / **EN** language in the sidebar.
7. **About** — author information and the **Donate / Thanks** tab.

### Useful features

- Saved connection profiles (passwords protected with DPAPI).
- Object notes (local under `%LOCALAPPDATA%\SQL Structure Reader\`).
- Schema quality warnings, mini column-relationship view.

### What the program does not do

Query Lab is limited to SELECT statements — it is not for data changes or server administration. It does not replace full tools such as SSMS for complex admin work.

### Author and terms

Maksym Goldevskyi. Copyright details: [About.txt](./About.txt).
