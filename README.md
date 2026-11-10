# TeklaPelletDroid

Aplikacja Android do sterowania kotłem pelletowym Tekla/Estyma przez moduł TeklaPelletCAN (urządzenie podłączane
do magistrali CAN kotła). Działa w tej samej sieci Wi‑Fi co moduł; znajduje go automatycznie albo po adresie IP.

## Co potrafi

- **Pulpit** (kocioł, palnik, CWU, CO, paliwo, alarmy, temperatury), **Instalacja** (schemat na żywo), **Nastawy**,
  **Alarmy** (historia, potwierdzanie), **Wszystkie parametry** z poziomami dostępu.
- **Poziomy kotła 1 i 2** (PIN jak w panelu kotła): klawiatura PIN, plakietka poziomu, autoblokada po 5 minutach
  bezczynności.
- **Tryb demo**: wirtualny kocioł z żywymi odczytami, bez sieci i bez modułu – do wypróbowania aplikacji.
- **Panel oryginalny** i **konfiguracja modułu** (aktualizacja oprogramowania, dziennik, Wi‑Fi) w osobnym oknie.
- Gdy moduł jest nieosiągalny: ostatnie znane wartości z godziną i baner „Brak połączenia z kotłem”.

## Instalacja

Pobierz `teklapelletcan.apk` z [wydań tego repozytorium](../../releases) i zainstaluj ręcznie (Android 10+; wymaga
zezwolenia na instalację z nieznanych źródeł).

## Bezpieczeństwo

PIN aplikacji (opcjonalny) chroni tylko uruchomienie aplikacji. Osobny PIN poziomu kotła (0900/0999, jak w panelu
fizycznym) chroni zapis parametrów i wygasa po 5 minutach bezczynności.

## Zastrzeżenia

Projekt niezależny i nieoficjalny, niezwiązany z firmami Tekla ani Estyma. **Nie jest zamiennikiem oryginalnego
sterownika kotła.** Zapis parametrów odbywa się na własne ryzyko i może naruszać warunki gwarancji producenta oraz
prowadzić do uszkodzenia lub nieprawidłowej pracy kotła/sterownika. Licencja: [LICENSE](LICENSE).
