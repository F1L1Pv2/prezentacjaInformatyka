---
marp: true
theme: default
paginate: true
class: invert
---

# Ustawienia sieciowe danego komputera i jego lokalizacji w sieci

Alan Klas & Filip Młodzik

---

# Plan prezentacji

1. Ustawienia sieciowe komputera
2. Adres IP
3. Maska podsieci
4. Brama domyślna
5. Serwery DNS
6. Adresacja IPv4 i IPv6
7. Przykład konfiguracji

---

# Ustawienia sieciowe komputera

- Ustawienia sieciowe komputera to konfiguracja parametrów sieciowych, które umożliwiają komunikację z innymi urządzeniami w sieci.
- Do podstawowych ustawień sieciowych należą: adres IP, maska podsieci, brama domyślna oraz serwery DNS.

---

# Adres IP

- Adres IP (Internet Protocol) to unikalny identyfikator przypisany do każdego urządzenia w sieci.
- Adres IP składa się z 4 grup liczb (w przypadku IPv4) lub 8 grup (w przypadku IPv6).
- Przykład adresu IPv4: 192.168.1.10
- Przykład adresu IPv6: 2001:0db8:85a3:0000:0000:8a2e:0370:7334

---

# Maska podsieci

- Maska podsieci służy do określenia, które części adresu IP są używane do identyfikacji sieci, a które do identyfikacji hosta.
- Maska podsieci składa się z 4 grup liczb (w przypadku IPv4) lub 8 grup (w przypadku IPv6).
- Przykład maski podsieci dla IPv4: 255.255.255.0
- Przykład maski podsieci dla IPv6: ffff:ffff:ffff:ffff::

---

# Brama domyślna

- Brama domyślna to adres IP urządzenia sieciowego (np. routera), który umożliwia komunikację z innymi sieciami.
- Brama domyślna jest używana, gdy komputer chce nawiązać połączenie z urządzeniem spoza swojej lokalnej sieci.
- Przykład adresu IP bramy domyślnej: 192.168.1.1

---

# Serwery DNS

- Serwery DNS (Domain Name System) to serwery odpowiedzialne za tłumaczenie nazw domen na adresy IP.
- Serwery DNS umożliwiają korzystanie z nazw domen (np. google.com) zamiast adresów IP.
- Przykład adresu IP serwera DNS: 8.8.8.8 (Google DNS)

---

# Adresacja IPv4 i IPv6

- IPv4 (Internet Protocol version 4) to czwarta wersja protokołu IP, która używa 32-bitowych adresów.
- IPv6 (Internet Protocol version 6) to szósta wersja protokołu IP, która używa 128-bitowych adresów.
- IPv6 został wprowadzony, aby rozwiązać problem wyczerpywania się puli adresów IPv4. W tej chwili nie jest on jeszcze powszechnie używany.

---

# Przykład konfiguracji

- Adres IP: 192.168.1.10
- Maska podsieci: 255.255.255.0
- Brama domyślna: 192.168.1.1
- Serwery DNS: 8.8.8.8, 8.8.4.4

---

# Podsumowanie

- Ustawienia sieciowe komputera to konfiguracja parametrów sieciowych, które umożliwiają komunikację z innymi urządzeniami w sieci.
- Podstawowe ustawienia sieciowe to: adres IP, maska podsieci, brama domyślna oraz serwery DNS.
- Adresacja IPv4 i IPv6 różni się liczbą bitów używanych do reprezentacji adresów IP.
