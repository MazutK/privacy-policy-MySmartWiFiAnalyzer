# Polityka Prywatności

## MySmartWiFiAnalyzer

**Data wejścia w życie:** 29 listopada 2025 roku

---

## 1. Wstęp

Niniejsza Polityka Prywatności („Polityka") opisuje, w jaki sposób aplikacja mobilna **MySmartWiFiAnalyzer** („Aplikacja") zbiera, wykorzystuje, przechowuje i chroni informacje użytkownika („Użytkownik", „Ty"). 

Aplikacja została opracowana w celu analizy sieci WiFi, wizualizacji mocy sygnału oraz ułatwienia diagnostyki łączności bezprzewodowej poprzez technologię Augmented Reality (AR).

Niniejsza Polityka jest zgodna z:
- **Rozporządzeniem Parlamentu Europejskiego i Rady (UE) 2016/679** (RODO)
- **Ustawą o ochronie danych osobowych** (Polska)
- **Ustawą o ochronie konkurencji i konsumentów** (Polska)

---

## 2. Administrator Danych

**Nazwa:** [Kacper Mazur]  
**Email:** [kacpermazur@onet.pl]  

W przypadku pytań dotyczących niniejszej Polityki Prywatności, skontaktuj się z nami na powyższy adres email.

---

## 3. Jakie Dane Zbieramy

### 3.1 Dane zbierane z uprawnień aplikacji

#### A) **Lokalizacja (Precise Location)**
- **Co zbieramy:** Precyjna lokalizacja geograficzna urządzenia (GPS)
- **Po co:** Aby wyświetlić dostępne sieci WiFi w Twojej okolicy i powiązać moc sygnału z lokalizacją na mapie
- **Czy przechowujemy:** Nie. Dane lokalizacji są przetwarzane lokalnie na Twoim urządzeniu i nie są wysyłane na serwer

#### B) **Dostęp do WiFi (Nearby WiFi Networks)**
- **Co zbieramy:** Lista dostępnych sieci WiFi (SSID, BSSID, moc sygnału w dBm, częstotliwość)
- **Po co:** Aby analizować dostępne sieci i wyświetlać ich charakterystyki
- **Czy przechowujemy:** Nie. Informacje o sieciach są przetwarzane lokalnie. Nie przechowujemy haseł ani informacji logowania

#### C) **Aparat fotograficzny (Camera)**
- **Co zbieramy:** Dostęp do aparatu
- **Po co:** Aby wyświetlać wizualizację AR (Augmented Reality) nakładającą dane sieciowe na obraz z aparatu
- **Czy przechowujemy:** Nie. Obraz z aparatu jest przetwarzany w czasie rzeczywistym i nie jest zapisywany ani przesyłany bez wyrażonej zgody użytkownika

#### D) **Pliki i Media (Optional)**
- **Co zbieramy:** Dostęp do pamięci wewnętrznej/karty SD
- **Po co:** Aby pozwolić na zapis zrzutów ekranu i raportów analizy
- **Czy przechowujemy:** Lokalnie na Twoim urządzeniu. Możesz te pliki udostępnić, ale to Twoja świadoma decyzja

### 3.2 Dane zbierane automatycznie

#### Diagnostyka i logi błędów
- **Co zbieramy:** Informacje o awariach aplikacji, stack traces, wersja systemu operacyjnego
- **Po co:** Aby ulepszyć stabilność aplikacji i naprawiać błędy
- **Czy przechowujemy:** Lokalnie na Twoim urządzeniu, chyba że wybierzesz wysłanie raportu diagnostycznego

#### Preferencje użytkownika
- **Co zbieramy:** Twoje ustawienia w aplikacji (np. preferencje wyświetlania, theme)
- **Po co:** Aby zapamiętać Twoje preferencje między sesjami
- **Gdzie:** Lokalnie na Twoim urządzeniu w SharedPreferences/DataStore

#### Dane o urządzeniu
- **Co zbieramy:** Model telefonu, wersja Androida, rozdzielczość ekranu
- **Po co:** Aby optymalizować aplikację dla różnych urządzeń
- **Czy przechowujemy:** Nie na serwerach - opcjonalnie w logach analitycznych (zobacz punkt 3.3)

### 3.3 Usługi analityczne 

Jeśli Aplikacja korzysta z Google Analytics lub podobnych usług:
- **Google Analytics:** Informacje o sposobie użytkowania aplikacji (liczba sesji, czas sesji, funkcje używane)
- **Więcej info:** [Polityka prywatności Google](https://policies.google.com/privacy)

**Możesz zrezygnować** z wysyłania danych analitycznych w ustawieniach aplikacji.

---

## 4. Baza Prawna Przetwarzania Danych

Przetwarzamy Twoje dane na podstawie:

| Dane | Baza prawna | Obowiązek |
|------|-----------|----------|
| Lokalizacja | Art. 6(1)(a) RODO - Wyrażona zgoda | TAK - musisz wyrazić zgodę w ustawieniach Androida |
| Dostęp do WiFi | Art. 6(1)(a) RODO - Wyrażona zgoda | TAK - musisz wyrazić zgodę w ustawieniach Androida |
| Aparat | Art. 6(1)(a) RODO - Wyrażona zgoda | TAK - musisz wyrazić zgodę w ustawieniach Androida |
| Dane diagnostyki | Art. 6(1)(b) RODO - Wykonanie umowy | Wymagane dla funkcjonalności aplikacji |
| Preferencje | Art. 6(1)(b) RODO - Wykonanie umowy | Wymagane dla funkcjonalności aplikacji |

---

## 5. Cel Przetwarzania Danych

Przetwarzamy Twoje dane w następujących celach:

1. **Świadczenie usługi** - Umożliwienie skanowania sieci WiFi i wizualizacji AR
2. **Poprawianie aplikacji** - Naprawa błędów i optymalizacja wydajności
3. **Bezpieczeństwo** - Zapobieganie nadużyciom i atakom na aplikację
4. **Zgodność z prawem** - Spełnianie wymogów prawnych i regulacyjnych

**Nie używamy Twoich danych do:**
- Sprzedaży danych osobom trzecim
- Targetowania reklam behawioralnych
- Profiling bez Twojej wiedzy
- Monitorowania aktywności na internecie poza aplikacją

---

## 6. Udostępnianie Danych Stronom Trzecim

### 6.1 Kiedy udostępniamy dane

- **Dostawcy usług:** Firebase, Google Cloud (jeśli używamy)
- **Wymóg prawny:** W przypadku żądania sądu lub organów ścigania
- **Bezpieczeństwo:** Jeśli podejrzewamy przestępstwo

### 6.2 Kiedy NIE udostępniamy

- **Dane lokalizacji** - Nigdy nie są wysyłane na serwer
- **Hasła WiFi** - Nigdy nie są przechwytywane lub wysyłane
- **Prywatne SSIDy** - Przetwarzane tylko lokalnie

### 6.3 Transfery międzynarodowe

Jeśli korzystamy z serwerów poza UE (np. Google Cloud US), dane są chronione poprzez **Clausule Kontraktowe Standardowe (SCC)** zgodnie z RODO.

---

## 7. Przechowywanie Danych

| Typ danych | Okres przechowywania | Lokacja |
|-----------|-------------------|---------|
| Dane w sesji (WiFi, lokalizacja, AR) | Tylko podczas sesji aplikacji | Urządzenie użytkownika |
| Preferencje użytkownika | Do czasu usunięcia aplikacji | Urządzenie użytkownika |
| Logi diagnostyki | 30 dni (jeśli wysłane) | Serwer (jeśli zdecydowano się na raport) |
| Dane Google Analytics | Zgodnie z polityką Google | Serwery Google |

**Usunięcie danych:** Po dezinstalacji aplikacji wszystkie dane lokalne są automatycznie usunięte.

---

## 8. Twoje Prawa

Na mocy RODO masz prawo do:

1. **Dostępu** - Wiesz, jakie dane o Tobie przetwarzamy
2. **Sprostowania** - Możesz poprosić o poprawę błędnych danych
3. **Usunięcia** - Prawo do "bycia zapomnianym" (z pewnymi wyjątkami)
4. **Ograniczenia** - Możesz ograniczyć przetwarzanie danych
5. **Przenoszenia** - Możesz otrzymać dane w formacie maszynowo czytelnym
6. **Sprzeciwu** - Możesz sprzeciwić się przetwarzaniu
7. **Wycofania zgody** - Możesz wycofać wcześniejszą zgodę w ustawieniach Androida

**Jak skorzystać:** Wyślij email na adres podany w punkcie 2 z zaznaczeniem, którego prawa chcesz skorzystać. Odpowiemy w ciągu 30 dni.

---

## 9. Bezpieczeństwo Danych

Wdrażamy następujące środki bezpieczeństwa:

- ✅ **Szyfrowanie transportu** - Połączenia HTTPS do serwerów
- ✅ **Lokalność danych** - Większość danych przetwarzana na urządzeniu
- ✅ **Brak logów hasła** - Hasła WiFi nigdy nie są zapisywane
- ✅ **Minimalizacja danych** - Zbieramy tylko dane niezbędne do funkcjonowania
- ✅ **Regularne audyty** - Sprawdzenie bezpieczeństwa aplikacji
- ✅ **Aktualizacje** - Szybkie łatki bezpieczeństwa

**Jednak:** Żaden system nie jest 100% bezpieczny. Jeśli podejrzewasz naruszenie danych, skontaktuj się z nami natychmiast.

---

## 10. Polityka Dotycząca Dzieci

Aplikacja nie jest przeznaczona dla osób poniżej **13 lat** (lub lokalnie obowiązującego wieku).

Nie zbieramy świadomie danych od dzieci. Jeśli okaże się, że zbieraliśmy dane od osoby poniżej 13 lat, usuniemy je natychmiast.

**Dla rodziców:** Jeśli Twoje dziecko użyło aplikacji bez zgody, skontaktuj się z nami na email podany w punkcie 2.

---

## 11. Pliki Cookie i Similar Technologies

Aplikacja mobilna **nie używa plików cookie** w tradycyjnym sensie. Jednak:

- **SharedPreferences/DataStore** - Przechowywanie preferencji lokalnie (analogiczne do cookies)
- **Identyfikatory urządzenia** - Android generuje unikalny ID dla celów analitycznych (możesz wyłączyć w ustawieniach)

---

## 12. Linki do Stron Trzecich

Aplikacja może zawierać linki do stron internetowych (np. polityka Google, strona autora). **Nie jesteśmy odpowiedzialni** za politykę prywatności tych stron. Każda strona ma swoją własną politykę.

---

## 13. Zmiany w Polityce Prywatności

Możemy aktualizować tę Politykę w dowolnym momencie. Jeśli będą istotne zmiany, powiadomimy Cię:
- Poprzez powiadomienie w aplikacji
- Poprzez update w Google Play z opisem zmian

**Data ostatniej aktualizacji:** 29 listopada 2025

Używając aplikacji po zmianach, akceptujesz nową Politykę.

---

## 14. Skargi do Organu Nadzoru

Jeśli uważasz, że przetwarzanie Twoich danych narusza RODO, możesz złożyć skargę do:

**Prezesa Urzędu Ochrony Danych Osobowych (PUODO)**
- Strona: [uodo.gov.pl](https://uodo.gov.pl)
- Email: [Formularz na stronie PUODO]
- Adres: ul. Stawki 2, 00-193 Warszawa

---

## 15. Kontakt

Jeśli masz pytania dotyczące tej Polityki Prywatności:

📧 **Email:** [kacpermazur@onet.pl]  

---

## 16. Podsumowanie Uprawnień i Ich Uzasadnienie

| Uprawnienie | Czemu jest potrzebne | Czy dane są przechowywane |
|-----------|-------------------|----------------------|
| ACCESS_FINE_LOCATION | Wyświetlanie lokalizacji na mapie AR | Nie - przetwarzane lokalnie |
| ACCESS_COARSE_LOCATION | Przybliżona lokalizacja dla sieci WiFi | Nie - przetwarzane lokalnie |
| ACCESS_WIFI_STATE | Skanowanie dostępnych sieci | Nie - przetwarzane lokalnie |
| CHANGE_WIFI_STATE | Zarządzanie WiFi (jeśli implementowane) | Nie - przetwarzane lokalnie |
| CAMERA | Wizualizacja AR sieci WiFi | Nie - przetwarzane w czasie rzeczywistym |
| READ_EXTERNAL_STORAGE | Zapis raportów | Lokalnie - użytkownik decyduje |
| INTERNET | Komunikacja z serwerami | Opcjonalne - tylko dla analytics |

---

**Dziękujemy za korzystanie z MySmartWiFiAnalyzer!** 🙏

*Niniejsza Polityka Prywatności weszła w życie 29 listopada 2025 roku.*
