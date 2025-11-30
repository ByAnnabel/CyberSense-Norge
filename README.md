🛡️ CyberSense Norge
AI-drevet simulator for digitale krisehendelser i Norge

CyberSense Norge er et fullstack-system som simulerer cyberangrep, kritiske systemfeil og infrastrukturhendelser i sanntid.
Prosjektet inkluderer backend (FastAPI) og frontend (React + Vite), og demonstrerer evne til å bygge komplette, moderne systemer fra ende til ende.

🚀 Hovedfunksjoner
🔥 Cyberangrep-simulator

Simulerer realistiske hendelser som:

DDoS

Ransomware

Systemsvikt

Datainnbrudd

Desinformasjon

Hendelser genereres med alvorlighetsgrad, tidsstempel, mål og beskrivelse.

🧠 AI-drevet analyse

Automatisk generert:

risikoanalyse

tiltak

vurdering av spredningsfare

tekstlig forklaring basert på hendelsens type

📊 Interaktivt dashboard

Frontend viser:

aktive hendelser

historikk

systemer som er rammet

status

AI-rådgiver

live feed

🧩 Teknologistack

Backend

FastAPI

Python

SQLAlchemy

Uvicorn

Frontend

React

Vite

Tailwind

Zustand

Axios

⚙️ Starte backend
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 -m uvicorn app.main:app --reload


Backend tilgjengelig på:
👉 http://127.0.0.1:8000

👉 http://127.0.0.1:8000/docs

🖥️ Starte frontend
cd frontend/cybersense-norge
npm install
npm run dev


Frontend tilgjengelig på:
👉 http://localhost:3000

📁 Prosjektstruktur
CyberSense-Norge/
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── models/
│   │   ├── routes/
│   │   └── schemas/
│   ├── venv/
│   ├── requirements.txt
│   └── .env (ikke inkludert)
│
└── frontend/
    └── cybersense-norge/
        ├── src/
        ├── components/
        ├── pages/
        ├── assets/
        └── package.json

🧪 API-endepunkter
Metode	Endpoint	Beskrivelse
POST	/api/incidents/simulate?count=3	Simuler nye hendelser
GET	/api/incidents/active	Hent aktive hendelser
GET	/api/incidents/history	Hendelseshistorikk
POST	/api/incidents/{id}/resolve	Marker hendelse som løst
GET	/api/incidents/{id}/advice	Hent AI-analyse
POST	/api/assets	Opprett nytt asset
GET	/api/assets	Hent alle registrerte assets
