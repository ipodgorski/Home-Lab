# 🏠 Domowe Laboratorium Serwerowe (Home Lab)

## 🎯 Cel projektu
Budowa i administracja domowym serwerem opartym na architekturze mikroserwisów (Docker). Projekt pokazuje proces przekształcenia starego laptopa (legacy hardware) w pełnoprawną jednostkę serwerową do testów sieciowych, monitoringu i automatyzacji.

### 💻 Wykorzystany sprzęt
* **Urządzenie:** Laptop Lenovo (bez portu Ethernet).
* **System:** Ubuntu Server 24.04 LTS (Headless).
* **Łączność:** Wyłącznie Wi-Fi (interfejs `wlp2s0`) ze statyczną adresacją IP.

---

## 📚 Spis Treści (Rozdziały)

### [Rozdział 1: Instalacja i konfiguracja sieci](./docs/01-instalacja-i-siec.md)
* Instalacja servera Ubuntu.
* Konfiguracja Netplan (Static IP, Wi-Fi).
* Optymalizacja zarządzania energią (Clamshell Mode).

### Rozdział 2: Konteneryzacja i Docker (Wkrótce)
* Instalacja silnika Docker oraz Docker Compose.
* Wdrożenie panelu Portainer do graficznego zarządzania kontenerami.

---

