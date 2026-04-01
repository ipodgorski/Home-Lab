# Rozdział 1: Instalacja systemu i konfiguracja sieci

## 1️⃣ Przygotowanie sprzętu
Instalacja odbyła się na starym laptopie Lenovo. Głównym wyzwaniem był brak portu Ethernet, co wymusiło konfigurację Wi-Fi (`wlp2s0`) w trybie tekstowym.

## 2️⃣ Konfiguracja Netplan (Static IP)
Zamiast DHCP, ustawiliśmy statyczny adres IP, aby serwer był zawsze dostępny pod tym samym adresem.

**Oto nasza konfiguracja YAML:**
![Netplan](../images/konfiguracja-netplan.png) 
*(Tu wstawisz nazwę swojego zdjęcia)*

## 3️⃣ Dostęp zdalny (SSH)
Połączyliśmy się z serwerem za pomocą Kali Linux. 
![SSH](../images/polaczenie-ssh.png)

## 4️⃣ Optymalizacja (Clamshell Mode)
Wyłączyliśmy usypianie laptopa po zamknięciu klapy w pliku `/etc/systemd/logind.conf`.
