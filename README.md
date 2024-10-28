# Skanner sieci Wi-Fi i wyświetlacz podłączonych urządzeń ESP32

## Opis
Ten projekt to prosty serwer WWW hostowany na mikrokontrolerze ESP32, zaprojektowany do wyświetlania pobliskich sieci Wi-Fi oraz podłączonych urządzeń. Serwer działa jako punkt dostępu (AP), do którego można się podłączyć za pomocą dowolnego urządzenia z obsługą Wi-Fi. Poprzez przyjazny interfejs webowy użytkownicy mogą przeglądać:

1. Listę dostępnych sieci Wi-Fi w zasięgu ESP32 wraz z siłą sygnału (RSSI).
2. Listę urządzeń podłączonych do punktu dostępu ESP32, wyświetlając adres MAC każdego urządzenia.

Interfejs użytkownika zaprojektowany jest w ciemnym motywie z neonowymi kolorami dla lepszej widoczności i estetyki.

![Projekt ESP32 Wi-Fi](https://cdn.discordapp.com/attachments/1296222763530584106/1300572636954365992/image.png?ex=67215428&is=672002a8&hm=9c886f3e1c6ad11490cf11a02ea84a367041e39402f4821460dccb4a9ba973dc&)

## Funkcje
- Wyświetlanie listy pobliskich sieci Wi-Fi z ich SSID i RSSI.
- Lista adresów MAC urządzeń podłączonych do ESP32 AP.
- Stylowy, responsywny design z użyciem układu CSS Grid.
- Migająca dioda LED wskazująca aktywność serwera.

> [!TIP]  
> Użyj płytki rozwojowej ESP32, powinna mieć ona wbudowaną diodę led oraz wejście na kabel (USB / USB-C)
![Przykładowa Płytka](https://cdn.discordapp.com/attachments/1296222763530584106/1300576392697872394/IMG_6544.jpg?ex=672157a7&is=67200627&hm=e5e0db81d7375b31cf65c3eedf682adb1397ed013f89d13bd552575ea02dc147&)

> [!NOTE]
> **PlatformIO**: Popularne rozszerzenie IDE do rozwijania projektów ESP32.
**Arduino IDE**: Do wgrania kodu na płytkę ESP32.

## Jak uruchomić
1. Skopiuj kod źródłowy do projektu w PlatformIO.
2. Podłącz płytkę ESP32 do komputera.
3. Wybierz odpowiednią płytkę w PlatformIO.
4. Wgraj kod na płytkę.
5. Po wgraniu kodu, otwórz przeglądarkę i wprowadź adres `http://192.168.4.1`, aby uzyskać dostęp do interfejsu.

## Autor
- **Miłosz Parzych**: [@lolowiczz](https://github.com/lolowiczz)

## Wsparcie
Jeśli masz pytania lub potrzebujesz pomocy, otwórz problem w repozytorium lub skontaktuj się ze mną bezpośrednio.

## Wkład
Czujesz się na siłach, by dodać coś do tego projektu? Napisz do mnie mailem a popracujemy razem!

![Mail](https://img.shields.io/badge/Email-mp@parzych.eu-blue?style=for-the-badge&logo=gmail&logoColor=white)
