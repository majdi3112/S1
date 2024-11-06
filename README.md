# Docker Webserver Project

Dit project bevat een eenvoudige configuratie voor een Docker-container die een webserver (NGINX) draait en een HTML-pagina serveert.

## Inhoud
- **Dockerfile**: De configuratie voor de Docker-container die NGINX installeert en de HTML-pagina serveert.
- **index.html**: Een HTML-bestand dat als welkomstpagina wordt weergegeven.

## Instructies voor gebruik
1. **Build de Docker-image**:
   ```bash
   docker build -t mijn-nginx-image .
