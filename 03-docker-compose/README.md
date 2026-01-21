# Docker Compose
## Beschrijving
Multi-container applicatie met Flask, PostgreSQL en Adminer.
## Bestanden
- `docker-compose.yml` - Compose definitie
- `Dockerfile` - Flask app image
- `app.py` - Flask applicatie
- `requirements.txt` - Python dependencies
## Gebruik
### Start applicatie
```bash
docker-compose up -d
```
### Testen
- Flask app: http://localhost:5000
- Adminer: http://localhost:8080