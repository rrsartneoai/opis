Narzędzia i Konfiguracja Środowiska
Visual Studio Code (VS Code)
Instalacja:

Pobierz i zainstaluj VS Code tutaj.
Rozszerzenia:

Markdownlint:
Zainstaluj rozszerzenie Markdownlint.
Dodaj konfigurację do settings.json:
JSON
{
  "markdownlint.config": {
    "MD013": { "line_length": 120 },
    "MD024": false
  }
}
 Public code references from 3 repositories
Prettier - Code formatter:
Zainstaluj rozszerzenie Prettier.
Dodaj konfigurację do .prettierrc.json:
JSON
{
  "printWidth": 120,
  "tabWidth": 2,
  "useTabs": false,
  "semi": true,
  "singleQuote": true,
  "trailingComma": "es5",
  "bracketSpacing": true,
  "arrowParens": "always"
}
 Public code references from 3 repositories
ESLint:
Zainstaluj rozszerzenie ESLint.
Dodaj konfigurację do .eslintrc.js:
JavaScript
module.exports = {
  "env": {
    "browser": true,
    "es2021": true
  },
  "extends": "eslint:recommended",
  "parserOptions": {
    "ecmaVersion": 12,
    "sourceType": "module"
  },
  "rules": {
    "indent": ["error", 2],
    "linebreak-style": ["error", "unix"],
    "quotes": ["error", "single"],
    "semi": ["error", "always"]
  }
};
 Public code references from 3 repositories
Mermaid Markdown Preview: Zainstaluj rozszerzenie.
Table of Contents Generator: Zainstaluj rozszerzenie, np. Markdown TOC.
Grammarly
Instalacja:

Zainstaluj rozszerzenie przeglądarki tutaj.
Konfiguracja:

Dostosuj ustawienia Grammarly do swoich preferencji (np. styl pisania, poziom formalności).
Prettier
Instalacja:

Zainstaluj Prettier globalnie: npm install -g prettier
Opcjonalnie, zainstaluj jako devDependency projektu: npm install --save-dev prettier
Konfiguracja:

Utwórz plik .prettierrc.json w głównym katalogu projektu i dodaj konfigurację.
Integracja z VS Code:

Skonfiguruj VS Code, aby automatycznie formatował pliki Markdown przy zapisie (Settings > Text Editor > Formatting > Format On Save).
ESLint
Instalacja:

Zainstaluj ESLint globalnie: npm install -g eslint
Opcjonalnie, zainstaluj jako devDependency projektu: npm install --save-dev eslint
Konfiguracja:

Utwórz plik .eslintrc.js w głównym katalogu projektu i dodaj konfigurację.
Integracja z VS Code:

Zainstaluj rozszerzenie ESLint w VS Code i skonfiguruj, aby automatycznie sprawdzał kod przy zapisie.
Mermaid / Draw.io / Excalidraw
Mermaid:

Nie wymaga instalacji, ponieważ jest renderowany przez rozszerzenie VS Code lub online.
Draw.io:

Dostępny online tutaj lub jako aplikacja desktopowa.
Excalidraw:

Dostępny online tutaj lub jako aplikacja desktopowa.
II. Proces Ulepszania Dokumentacji
Analiza istniejącej dokumentacji:

Przeczytaj uważnie plik Architecture.md.
Zidentyfikuj obszary wymagające poprawy i miejsca, gdzie można dodać diagramy i wizualizacje.
Aktualizacja struktury dokumentu:

Dodaj Table of Contents na początku dokumentu za pomocą rozszerzenia VS Code.
Zoptymalizuj strukturę dokumentu, dodając lub usuwając sekcje i podsekcje.
Poprawa formatowania i pisowni:

Uruchom Grammarly i Prettier, aby sprawdzić pisownię, gramatykę i formatowanie.
Sprawdź dokument ręcznie, aby upewnić się, że wszystko jest spójne i czytelne.
Dodawanie diagramów i wizualizacji:

Utwórz diagramy za pomocą Mermaid, Draw.io lub Excalidraw i dodaj je do dokumentu.
Dodaj krótkie podpisy do diagramów, wyjaśniające co przedstawiają.
Dodawanie szczegółów i przykładów użycia:

Rozwiń opisy komponentów i funkcji.
Dodaj przykłady użycia i scenariusze.
Aktualizacja przykładów kodu:

Sprawdź, czy przykłady kodu są aktualne i zgodne z najnowszymi praktykami.
Uruchom ESLint, aby sprawdzić poprawność kodu i naprawić błędy.
Sformatuj kod za pomocą Prettier.
Dodawanie linków do zasobów:

Dodaj linki do dokumentacji, tutoriali i artykułów.
Upewnij się, że wszystkie linki działają.
Dodawanie sekcji feedback:

Dodaj sekcję, w której użytkownicy mogą zostawić swoje uwagi i sugestie dotyczące dokumentacji.
Review i testy:

Poproś kogoś innego o przeczytanie dokumentu i zgłoszenie uwag.
Przetestuj wszystkie przykłady kodu i upewnij się, że działają poprawnie.
Sprawdź, czy wszystkie linki działają.
III. Przykładowe implementacje
Markdownlint
W VS Code otwórz paletę poleceń (Ctrl+Shift+P) i wpisz "Open Settings (JSON)".
Dodaj konfigurację markdownlint do pliku settings.json.
Prettier
W VS Code otwórz paletę poleceń (Ctrl+Shift+P) i wpisz "Format Document".
Wybierz "Prettier" jako formatter.
Skonfiguruj automatyczne formatowanie przy zapisie w ustawieniach VS Code.
ESLint
Otwórz terminal i uruchom eslint . w głównym katalogu projektu, aby sprawdzić wszystkie pliki JavaScript.
Napraw błędy zgłoszone przez ESLint.
Diagramy
Otwórz Draw.io lub Excalidraw i utwórz diagram przedstawiający architekturę systemu.
Wyeksportuj diagram jako obraz (np. PNG lub SVG).
Dodaj obraz do dokumentu Markdown, używając składni ![Alt text](path/to/image.png).
Alternatywnie, utwórz diagram za pomocą Mermaid i dodaj kod Mermaid do dokumentu Markdown.
Spis Treści (TOC)
Użyj rozszerzenia VS Code do automatycznego generowania TOC.
Upewnij się, że wszystkie linki w TOC działają poprawnie.
