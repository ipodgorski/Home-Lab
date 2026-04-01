# Rozdział 2: Serce serwera - Docker i Portainer

## 🐳 Dlaczego konteneryzacja?
Zamiast instalować aplikacje bezpośrednio w systemie operacyjnym, zdecydowałem się na wykorzystanie **Dockera**. Pozwala to na pełną izolację usług, łatwe zarządzanie ich cyklem życia oraz zachowanie czystości w głównym systemie (Ubuntu).

## 🛠 Wdrożenie silnika Docker
Instalacja obejmowała:
* `docker.io`: Silnik uruchamiający kontenery.
* `docker-compose`: Narzędzie do definiowania wielokontenerowych aplikacji.
* Konfigurację uprawnień użytkownika, aby umożliwić zarządzanie bez stałego użycia `sudo` (bezpieczeństwo operacyjne).

## 📊 Panel zarządzania Portainer
Aby uzyskać pełną kontrolę nad infrastrukturą, wdrożyłem **Portainer CE**. Jest to interfejs graficzny, który pozwala na monitoring zasobów i zarządzanie kontenerami w czasie rzeczywistym.

**Widok główny panelu Portainer (Dashboard):**
![Dashboard Portainera](../images/portainer-main.png)

> **Kluczowa umiejętność:** Zarządzanie kontenerami poprzez "Docker Socket" oraz mapowanie portów (9443 dla HTTPS), co pozwala na bezpieczną administrację z zewnątrz.
