# Stacja Lublin — wydania na Raspberry Pi

Podpisane paczki aktualizacji aplikacji panelu pogodowego.

Najnowszy instalator jest dostępny w sekcji Releases jako Stacja-Raspberry-Pi.zip.
System Raspberry Pi OS z pulpitem nagrywa się osobno przez Raspberry Pi Imager.

W panelu wybierz zębatkę ustawień i Aktualizacje.
Sprawdzanie nowych wersji odbywa się po starcie i co 6 godzin.
Instalację zatwierdza użytkownik. Aktualizator weryfikuje podpis Ed25519
oraz SHA-256 paczki i przechowuje poprzednią wersję.

manifest.json zawiera podpisany opis wydania. panel-VERSION.zip zawiera
pliki aplikacji. Klucz publiczny jest dołączony do instalatora.

Testy funkcji i scenariuszy przywracania wykonano na komputerze.
Pierwsza instalacja, usługi systemd, ekran dotykowy i DRM SWEET.TV
wymagają weryfikacji na fizycznym Raspberry Pi.
