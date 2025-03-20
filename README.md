

**1. Opis Systemu:**

*   "System monitoruje jakość powietrza i zarządza infrastrukturą monitoringu w czasie rzeczywistym.  Umożliwia:" 
*   "Główne funkcjonalności systemu obejmują:" 
*   "Integruje się z zewnętrznymi systemami pomiarowymi."

**2. Główne Komponenty:**

*   **Monitoring jakości powietrza (src/components/dashboard/AirQualityChart.tsx):**
    *   "Komponent wyświetla interaktywne wykresy jakości powietrza." 
    *   "Umożliwia przełączanie między różnymi typami wykresów." 
    *   "Oferuje eksport danych do formatów PDF i JPG."
    *   "Dostępne są funkcje przybliżania i szczegółowej analizy danych."
*   **Statystyki Mocy (src/components/dashboard/PowerStats.tsx):**
    *   "Komponent wyświetla kluczowe wskaźniki w formie kart." 
    *   "Animowane wskaźniki statusu wizualizują bieżący stan."
    *   "Wykresy trendów przedstawiają historię zmian w czasie."
*   **Status Urządzeń (src/components/network/DeviceStatus.tsx):**
    *   "Komponent monitoruje status transformatorów, liczników energii i parametrów czujników." 
*   **Analiza Awarii (src/components/network/FailureAnalysis.tsx):**
    *   "System wykrywa problemy w oparciu o zdefiniowane reguły." 
    *   "Proponuje rekomendacje naprawcze."
    *   "Przechowuje historię awarii."

**Punkty dostosowania:**  Można dodać krótkie wyjaśnienie, *jak* te punkty dostosowania wpływają na działanie komponentu (np. "Zmiana koloru linii pozwala na dostosowanie wyglądu wykresu do własnych preferencji wizualnych.").

**3. Przepływ Danych:**

*   "System przetwarza dane w dwóch głównych przepływach: monitorowanie w czasie rzeczywistym i analiza wydajności." 

**4. Kluczowe Technologie:**

*   "Frontend został zbudowany w oparciu o następujące technologie:" 
*   "Responsywne wykresy oparte o bibliotekę Recharts oferują interaktywne elementy i pozwalają na customizację stylów."
*   "UI Framework: Tailwind CSS + shadcn/ui zapewnia system projektowania, komponenty wielokrotnego użytku i responsywny układ."
*   "Animacje Framer Motion zapewniają płynne przejścia i interaktywne elementy wykresów."

**5. Architektura Danych:**

*   "System wykorzystuje następujące interfejsy danych:" 
*   Można dodać krótkie wyjaśnienie, jak te dane są wykorzystywane w systemie.

**6. Planowane Ulepszenia:**

*   "Planowane są następujące ulepszenia systemu:" 
*   "Zaawansowana Analityka: Wykorzystanie Machine Learning do predykcji awarii, automatycznej optymalizacji zużycia i detekcji anomalii." 

**7. Struktura Komponentów:**  (

**8. Kluczowe Miejsca do Dostosowania:**

*   "System oferuje szereg miejsc, w których można dostosować jego działanie i wygląd:" (wprowadzenie)
*   "Dane Firm (src/data/companies/):  Tutaj można zmodyfikować dane firmy, takie jak nazwa i statystyki dotyczące jakości powietrza."
*   "Komponenty UI (src/components/ui/):  Umożliwia customizację wyglądu komponentów za pomocą stylów CSS."
*   "Tłumaczenia (src/i18n/translations/):  Dodawanie nowych tłumaczeń pozwala na lokalizację interfejsu."
*   "Konfiguracja Wykresów (src/components/dashboard/):  Pozwala na dostosowanie kolorów, animacji i tooltipów wykresów."
*   "System Alertów (src/components/network/):  Umożliwia konfigurację progów alertów oraz kanałów powiadomień (email, push, sms)."

**9. Asystent AI RAG:**

*   "Asystent AI wykorzystuje architekturę Retrieval-Augmented Generation (RAG) do dostarczania inteligentnych informacji i odpowiedzi dotyczących jakości powietrza użytkownikom." 
*   "Architektura RAG opiera się na następujących krokach:" 
*   **Pobieranie:** "System pobiera odpowiednie dokumenty z bazy wiedzy w oparciu o zapytanie użytkownika."
*   **Generowanie:** "Pobrane dokumenty są łączone z zapytaniem użytkownika i przekazywane do modelu językowego (LLM)."
*   **Wyjście:** "LLM generuje spójną odpowiedź na zapytanie użytkownika na podstawie pobranej wiedzy."
*   "Kluczowe komponenty Asystenta AI to:" 

**10. Pomorska Mapa Jakości Powietrza:**

*   "Pomorska Mapa Jakości Powietrza wizualizuje dane dotyczące jakości powietrza w województwie pomorskim." 
*   "Celem mapy jest:" 
*   "Wizualizacja: Mapa wykorzystuje kolorowe znaczniki i mapy cieplne do reprezentowania poziomów zanieczyszczeń powietrza."





---



**1. Opis Systemu:**

*   "System monitoruje jakość powietrza i zarządza infrastrukturą monitoringu w czasie rzeczywistym. Umożliwia integrację z zewnętrznymi systemami pomiarowymi."

**2. Główne Komponenty:**

*   **Monitoring jakości powietrza (src/components/dashboard/AirQualityChart.tsx):** "Komponent wyświetla interaktywne wykresy jakości powietrza z funkcjami eksportu (PDF, JPG) i szczegółowej analizy."
*   **Statystyki Mocy (src/components/dashboard/PowerStats.tsx):** "Komponent prezentuje kluczowe wskaźniki, animowane statusy i wykresy trendów."
*   **Status Urządzeń (src/components/network/DeviceStatus.tsx):** "Komponent monitoruje status transformatorów, liczników energii i parametrów czujników."
*   **Analiza Awarii (src/components/network/FailureAnalysis.tsx):** "System wykrywa problemy, proponuje rekomendacje naprawcze i archiwizuje historię awarii."

  
**3. Przepływ Danych:**

*   "System przetwarza dane w dwóch głównych przepływach: monitorowanie w czasie rzeczywistym i analiza wydajności."

**4. Kluczowe Technologie:**

*   "Frontend: React + TypeScript. Wykorzystano responsywne wykresy Recharts, UI Framework Tailwind CSS + shadcn/ui, oraz animacje Framer Motion."

**5. Architektura Danych:**

*   "System definiuje interfejsy danych dla czujników, alertów i danych historycznych."

**6. Planowane Ulepszenia:**

*   "Zaawansowana analityka (Machine Learning dla predykcji awarii, optymalizacji) oraz rozszerzone możliwości eksportu."

**7. Struktura Komponentów:**

**8. Kluczowe Miejsca do Dostosowania:**

*   "System oferuje konfigurację danych firm, komponentów UI (style CSS), tłumaczeń, wykresów i alertów."

**9. Asystent AI RAG:**

*   "Asystent AI (RAG) dostarcza inteligentne informacje o jakości powietrza. Architektura: Pobieranie -> Generowanie (LLM) -> Wyjście."
*   "Kluczowe komponenty Asystenta AI:" _(Wyliczyć komponenty jeśli konieczne)_

**10. Pomorska Mapa Jakości Powietrza:**

*   "Mapa wizualizuje dane o jakości powietrza w województwie pomorskim."
*   "Cel: informowanie i podnoszenie świadomości na temat jakości powietrza."



