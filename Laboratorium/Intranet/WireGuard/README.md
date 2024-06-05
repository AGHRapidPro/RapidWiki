# WireGuard

## Czym jest Wireguard VPN?

WireGuard jest powszechnie uznawany za najszybszy, najbezpieczniejszy i najprostszy protokół VPN. Został zaprojektowany z myślą o zastąpieniu starszych protokołów VPN, takich jak PPTP, SSTP, OpenVPN czy te oparte na IPSec.

Czy wspomnieliśmy, że jest open-source, dostępny w jądrze Linuxa oraz że podczas bardzo dociekliwych audytów nie wykazano żadnych podatności?

## Po co mi VPN?

W naszej organizacji mamy wiele urządzeń, które do swojej obsługi wykorzystują połączenie z siecią. Świetnym przykładem są nasze drukarki! Dzięki połączeniu z Wi-Fi możemy korzystać z PrusaLink, Voronów, Epsonów itp. do pracy. Co jednak w przypadku, gdybyśmy chcieli używać tych urządzeń z naszego domu?

Tutaj z pomocą przychodzi WireGuard. Nasz VPN umożliwia zdalny dostęp do naszej lokalnej sieci, w której znajdują się wszystkie nasze urządzenia.

## Ważna uwaga!

Nasz VPN nie routuje całego twojego ruchu sieciowego do D!, tylko adresy z podsieci wykorzystywanej w laboratorium (192.168.69.0/24). Oznacza to, że wchodząc na dowolną stronę internetową, ruch będzie szedł z twojego routera, ale w przypadku, gdy będziemy chcieli dostać się do komputera w laboratorium albo puścić wydruk, takie połączenia będą możliwe dla twojego komputera.

## Instalacja i konfiguracja WireGuard

### Instalacja WireGuard

Żeby zainstalować klienta WireGuard, wystarczy [wejść na ich stronę](https://www.wireguard.com/install/) i naklikać co trzeba. Jeżeli naprawdę jesteście uparci, to na [Google Play Store](https://play.google.com/store/apps/details?id=com.wireguard.android&pli=1) oraz na [App Store](https://apps.apple.com/us/app/wireguard/id1441195209?ls=1) też jest wersja mobilna.

### Jak skonfigurować Wireguard-a na moim urządzeniu?

1. todo
