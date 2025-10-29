  📚 Bookly – Wypożyczalnia książek online
🧭 Wizja produktu

Bookly to nowoczesna platforma webowa umożliwiająca użytkownikom wypożyczanie książek online w modelu subskrypcyjnym.
Celem projektu jest digitalizacja klasycznego procesu wypożyczania książek, zapewnienie wygodnego dostępu do bogatego katalogu tytułów oraz prostej obsługi użytkowników i płatności.

🎯 Cele projektu

Udostępnienie intuicyjnego interfejsu do przeglądania, wyszukiwania i wypożyczania książek.

Wprowadzenie subskrypcji premium z dodatkowymi korzyściami (np. większy limit wypożyczeń).

Automatyzacja zarządzania katalogiem i użytkownikami poprzez panel administratora.

Integracja z bezpiecznymi systemami płatności online.

  🏗️ Zakres funkcjonalny
🔑 System kont użytkowników

Rejestracja i logowanie użytkowników.

Resetowanie hasła i edycja profilu.

Zarządzanie aktywnymi wypożyczeniami.

📖 Katalog książek

Przeglądanie listy książek według kategorii i gatunku.

Wyszukiwanie po tytule, autorze i słowach kluczowych.

Szczegółowe informacje o książkach i opinie użytkowników.

🔄 System wypożyczania

Rezerwacja i wypożyczanie książek online.

Historia wypożyczeń i terminy zwrotów.

Automatyczne powiadomienia o zbliżających się zwrotach.

💳 Płatności i subskrypcje

Wykupienie planu subskrypcji (miesięcznej lub rocznej).

Integracja z bramkami płatności (Stripe / PayU / Braintree).

Podgląd historii płatności i statusu subskrypcji.

🛠️ Panel administratora

Zarządzanie użytkownikami, książkami i subskrypcjami.

Dodawanie, edytowanie i usuwanie pozycji z katalogu.

Przegląd raportów i statystyk aktywności systemu.

🧩 Technologia i narzędzia

Frontend: React / Next.js

Backend: Node.js (Express)

Baza danych: Azure SQL / MongoDB

CI/CD: Azure Pipelines

Hosting: Azure App Service

🚀 Pipeline CI/CD (skrót)

Pipeline w Azure DevOps buduje, testuje i wdraża aplikację po każdej aktualizacji w gałęzi main.
Proces obejmuje:

Instalację zależności (Node.js 18.x)

Budowę aplikacji (npm run build)

Uruchomienie testów (npm test)

Automatyczne wdrożenie na środowisko testowe

📊 Struktura backlogu

Hierarchia elementów w Azure Boards:

Epic: Wizja produktu – Bookly

Epik: System kont użytkowników

Feature: Rejestracja użytkownika

User Story: Rejestracja nowego konta

Epik: Katalog książek

Feature: Wyszukiwanie i filtrowanie

User Story: Wyszukiwanie po tytule

Epik: System wypożyczania

Epik: Płatności i subskrypcje

Epik: Panel administratora

💡 Wartości dla użytkowników

Dostęp do szerokiego katalogu książek 24/7.

Prosty i szybki proces wypożyczania.

Możliwość korzystania z planów subskrypcyjnych.

Transparentny system zarządzania kontem i płatnościami.

🧱 Kolejne kroki rozwoju

Integracja z API bibliotek partnerskich.

Dodanie rekomendacji książek opartych o historię czytania.

Aplikacja mobilna (React Native / Flutter).

Funkcja społecznościowa – recenzje i oceny użytkowników.
