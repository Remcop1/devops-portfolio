# Docker Advanced
## Beschrijving
Geavanceerde Docker concepten: volumes, networks, environment variabelen.
## Bestanden
- `Dockerfile` - Image definitie
- `app.py` - Flask applicatie
- `requirements.txt` - Python dependencies
## Gebruik
### Image bouwen
```bash
docker build -t mijn-flask-app .
```
### Container starten
```bash
docker run -d -p 5000:5000 --name flask-app mijn-flask-app
```
### Testen
Open browser: http://localhost:5000