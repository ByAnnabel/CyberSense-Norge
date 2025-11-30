🛡️ CyberSense Norge

AI-drevet simulator for digitale krisehendelser i Norge.

CyberSense Norge er et fullstack-prosjekt som simulerer cyberangrep, kritiske systemfeil og infrastrukturhendelser i sanntid. Dashbordet gir oversikt over aktive hendelser, rammede systemer, alvorlighetsgrad, tidslinjer og AI-generert situasjonsvurdering via Gemini.

Prosjektet er designet for portefølje og demonstrerer ferdigheter innen:

Backend/API-utvikling (FastAPI)

Frontend-utvikling (React + Vite)

Real-time simulering

Fullstack-struktur

Systemdesign og UI/UX for sikkerhetsoperasjoner

🚀 Funksjoner

Simulering av cyberangrep (DDoS, ransomware, desinformasjon m.m.)

Realtids-oppdateringer i dashboard

Hendelseslogg

Systemstatus og rammede noder

AI-genererte analyser basert på hendelsene

Full API-dokumentasjon via /OpenAPI

Norsk språk, tilpasset offentlig og privat sektor

🧩 Teknologier
Backend

Python 3.11

FastAPI

Uvicorn

Pydantic

CORS + REST API-struktur

Frontend

React (Vite)

TailwindCSS

Axios

Zustand (state)

Full dark-mode dashboard

📦 Installer og kjør prosjektet lokalt
1. Klon repoet
git clone https://github.com/ByAnnabel/CyberSense-Norge.git
cd CyberSense-Norge

⚙️ Start backend
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 -m uvicorn app.main:app --reload


Backend kjører nå på:

👉 http://127.0.0.1:8000

👉 Docs: http://127.0.0.1:8000/docs

🖥️ Start frontend
cd frontend/cybersense-norge
npm install
npm run dev


Frontend åpnes på:
👉 http://localhost:3000/

🧪 API-endepunkter

GET /api/incidents/active

GET /api/incidents/history

POST /api/incidents/simulate?count=3

POST /api/incidents/{id}/resolve

GET /api/incidents/{id}/advice

POST /api/assets – opprett nye systemer

Full dokumentasjon: http://127.0.0.1:8000/docs

📁 Prosjektstruktur
CyberSense-Norge/
│── backend/
│   ├── app/
│   ├── models/
│   ├── routes/
│   └── main.py
│
│── frontend/
│   └── cybersense-norge/
│       ├── src/
│       ├── components/
│       └── pages/
│
└── LICENSE

📜 Lisens

MIT-lisens. Fri bruk og modifikasjon.

🧠 Formål

Dette prosjektet er utviklet som en del av min portefølje for å vise:

evne til å bygge komplette fullstack-systemer

kompetanse innen sikkerhet & simuleringer

moderne UI-design

integrasjon av AI i operative dashboards
