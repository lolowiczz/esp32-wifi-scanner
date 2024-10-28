# Skanner sieci Wi-Fi i wyświetlacz podłączonych urządzeń ESP32

## Opis
Ten projekt to prosty serwer WWW hostowany na mikrokontrolerze ESP32, zaprojektowany do wyświetlania pobliskich sieci Wi-Fi oraz podłączonych urządzeń. Serwer działa jako punkt dostępu (AP), do którego można się podłączyć za pomocą dowolnego urządzenia z obsługą Wi-Fi. Poprzez przyjazny interfejs webowy użytkownicy mogą przeglądać:

1. Listę dostępnych sieci Wi-Fi w zasięgu ESP32 wraz z siłą sygnału (RSSI).
2. Listę urządzeń podłączonych do punktu dostępu ESP32, wyświetlając adres MAC każdego urządzenia.

Interfejs użytkownika zaprojektowany jest w ciemnym motywie z neonowymi kolorami dla lepszej widoczności i estetyki.

![Projekt ESP32 Wi-Fi](https://cdn.discordapp.com/attachments/1296222763530584106/1300572636954365992/image.png?ex=67215428&is=672002a8&hm=9c886f3e1c6ad11490cf11a02ea84a367041e39402f4821460dccb4a9ba973dc&)

## Technologie
Projekt został zrealizowany z wykorzystaniem następujących języków i technologii:
- ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)Główny język użyty do programowania ESP32.
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) Użyty do tworzenia struktury strony internetowej.
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) Użyty do stylizacji interfejsu użytkownika.
- ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white) Platforma programistyczna dla ESP32.
- ![PlatformIO](https://img.shields.io/badge/PlatformIO-000000?style=for-the-badge&logo=platformio&logoColor=white) Środowisko do zarządzania projektami.

## Funkcje
- Wyświetlanie listy pobliskich sieci Wi-Fi z ich SSID i RSSI.
- Lista adresów MAC urządzeń podłączonych do ESP32 AP.
- Stylowy, responsywny design z użyciem układu CSS Grid.
- Migająca dioda LED wskazująca aktywność serwera.

> [!TIP]  
> Użyj płytki rozwojowej ESP32, powinna mieć ona wbudowaną diodę led oraz wejście na kabel (USB / USB-C)
![Przykładowa Płytka](https://cdn.discordapp.com/attachments/1296222763530584106/1300576392697872394/IMG_6544.jpg?ex=672157a7&is=67200627&hm=e5e0db81d7375b31cf65c3eedf682adb1397ed013f89d13bd552575ea02dc147&)

> [!NOTE]
> Używam **PlatformIO** jako popularne rozszerzenie IDE do rozwijania projektów ESP32 oraz **Arduino IDE** do wgrania kodu na płytkę ESP32.

## Jak uruchomić
1. Skopiuj kod źródłowy do projektu w PlatformIO.
2. Podłącz płytkę ESP32 do komputera.
3. Wybierz odpowiednią płytkę w PlatformIO.
4. Wgraj kod na płytkę.
5. Po wgraniu kodu, otwórz przeglądarkę i wprowadź adres `http://192.168.4.1`, aby uzyskać dostęp do interfejsu.

## Autor
- **Miłosz Parzych**:
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/lolowiczz/)
[![Website](https://img.shields.io/badge/Portfolio-Visit%20My%20Website-green)](https://codelaunch.pl)
[![Discord](https://img.shields.io/discord/your-discord-server-id?label=Join%20Discord&logo=discord&style=for-the-badge)](https://discord.gg/HJTDT2Y9aC)


## Wsparcie
Jeśli masz pytania lub potrzebujesz pomocy, otwórz problem w repozytorium lub skontaktuj się ze mną bezpośrednio.

## Wkład
Czujesz się na siłach, by dodać coś do tego projektu? Napisz do mnie mailem a popracujemy razem!

![Mail](https://img.shields.io/badge/Email-mp@parzych.eu-blue?style=for-the-badge&logo=gmail&logoColor=white)
