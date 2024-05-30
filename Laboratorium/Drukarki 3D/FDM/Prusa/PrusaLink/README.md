# PrusaLink

PrusaLink to lokalnie działająca usługa hostowana przez drukarkę 3D i umożliwiająca zarówno zdalne drukowanie, jak i zarządzanie maszyną. PrusaLink obsługiwany jest przez wszystkie drukarki 3D Prusa Research z firmware 3.10.0 lub nowszym, z wbudowaną kartą sieciową.

**TL;DR**
PrusaLink jest dostępny na wszystkich Prusach w labie z wyłączeniem Prus MK3

## Before we start

Każde urządzenie podłączone do sieci wewnętrznej ma przypisany statyczny reokrd DNS. W przypadku Prus, rekordy te wyglądają następująco:

- Lewy Miniacz: [minil.rapid.internal](http://minil.rapid.internal)
- Prawy Miniacz: [minir.rapid.internal](http://minir.rapid.internal)
- Susa: [mk4sus.rapid.internal](http://mk4sus.rapid.internal)
- MK4 Enclosure: [mk4e.rapid.internal](http://mk4e.rapid.internal)

Każdy z podanych adresów jest podstawowym mechanizmem komunikacji z drukarkami - adresy IP **nie powinny** być używane do konfiguracji **czegokolwiek** w sieci, ze wzglądu na ich zmienność. URL'e z naszego DNSa są stałe, natomiast zawsze powinny prowadzić do aktualnego adresu IP danego urządzenia.
