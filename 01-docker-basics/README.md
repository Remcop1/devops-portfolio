# Docker Basics - Nginx Webserver
## Beschrijving
Een simpele nginx webserver met custom HTML pagina in een Docker
container.
## Bestanden
- `Dockerfile` - Image definitie
- `index.html` - Custom homepage
## Gebruik
### Image bouwen
```bash
docker build -t mijn-nginx .
```
### Container starten
```bash
docker run -d -p 8080:80 --name web mijn-nginx
```
### Testen
Open browser: http://localhost:8080