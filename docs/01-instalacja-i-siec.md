# Rozdział 1: Instalacja systemu i konfiguracja sieci
## 🏗️ Architektura Systemu
Projekt opiera się na modelu Klient-Serwer:
* **SERWER (Host):** Laptop Lenovo z systemem Ubuntu Server 24.04 LTS (Headless). To tutaj działają wszystkie usługi i kontenery.
* **KLIENT (Stacja zarządzająca):** Kali Linux (uruchomiony na maszynie wirtualnej VMware). Wykorzystywany jako główne narzędzie do bezpiecznej administracji, konfiguracji sieciowej i zarządzania serwerem przez protokół SSH.

## 1️⃣ Przygotowanie sprzętu
Instalacja odbyła się na laptopie Lenovo. Brak portu Ethernet, co wymusiło konfigurację Wi-Fi (`wlp2s0`) w trybie tekstowym.

## 2️⃣ Konfiguracja Netplan (Static IP)
Zamiast DHCP, ustawiliśmy statyczny adres IP, aby serwer był zawsze dostępny pod tym samym adresem.

**Oto nasza konfiguracja YAML:**


![Netplan](/docs/siec.png) 

## 3️⃣ Dostęp zdalny (SSH)
Połączyliśmy się z serwerem za pomocą Kali Linux. 
![SSH](/docs/ssh.png)

## 4️⃣ Optymalizacja (Clamshell Mode)
Wyłączyliśmy usypianie laptopa po zamknięciu klapy w pliku `/etc/systemd/logind.conf`.
