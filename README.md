# iRyś

![](/img/rendery%20v2/irys2.JPG)

# Abstrakt
Projekt zespołu balansujących robotów mobilnych. Zadaniem grupy robotów będzie poruszanie się w zamkniętej przestrzeni i współpraca przy przesuwaniu obiektów. 

## Funkcjonalność 
* Lokalizacja w przestrzni zamkniętej ograniczinej nadajnikami
* Przesyłanie obrazu i danych z czujników w sieci WLAN
* Mapowanie przestrzeni
* Sterowanie za pomocą aplikacji mobilnej
* Programowanie "On air" poszczególnych robotów 

## Elementy
### Napęd
* Silnki krokowe typu NEMA 17
* Sterowniki DRV8825

### Elektronika
* BeagleBone Green Wireless
* Transceiver DMW1000 (lokalizacja)

### Sensoryka
* Czujniki odległości (ultradźwiękowe)
* IMU MPU6050
* Gniazda do podłączenia innych czujników (w zależonści od wykorzystania)

## Wykonanie
Projekt zakłada stworzenie uniwersalnej płyty głównej robota scalającej wszyskie moduły, umożliwiającej proste podłączenie wszystkich elementów i ramy wydrukowanej na drukarce 3D. Dodatkowo w skład zestawu wchodziły bedą moduły lokalizacji (do umieszczenia wewnątrz pomieszczenia jako punkty odniesienia przy lokalizacji). Do organizacji pracy zespołu robotów zostanie opracowane oprogramowanie w języku C++ zaimplementowane na komputerze pełniącym jednocześnie rolę routera WiFi z którym będą połączone wszystkie roboty. 

![](/img/img/z raportu/konstrukcja/zielonyrys.jpg)


