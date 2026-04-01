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

## Instalacja

![Instalacja](/docs/poirtrainer.png)


**Widok główny panelu Portainer (Dashboard):**

![Dashboard Portainera](/docs/widok.png)


