# Import/Export Analyse App

## Instructies voor deployment op Render

1. Maak een PostgreSQL database aan op Render.
2. Voeg `DATABASE_URL` toe aan de backend Environment Variables.
3. Deploy backend als Web Service (Python, rootDir: `backend`).
4. Deploy frontend als Static Site (rootDir: `frontend`).
5. Frontend communiceert met backend via API URL.
6. Gebruik `render.yaml` voor automatische configuratie.
