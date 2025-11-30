🛡️ CyberSense Norge
AI-drevet simulator for digitale krisehendelser i Norge

CyberSense Norge er et fullstack-system som simulerer cyberangrep, kritiske systemfeil og infrastrukturhendelser i sanntid.
Prosjektet inkluderer både backend (FastAPI) og frontend (React + Vite), og demonstrerer evne til å bygge komplette, moderne IT-systemer fra ende til ende.

Dette prosjektet viser ferdigheter innen fullstack-utvikling, API-design, systemarkitektur, sikkerhetssimulering og AI-integrasjon.


🚀 Hovedfunksjoner
🔥 Cyberangrep-simulator

Simulerer realistiske digitale hendelser som:

DDoS

Ransomware

Systemsvikt

Datainnbrudd

Desinformasjon

Hver hendelse kobles til et asset i databasen med:

alvorlighetsgrad

tidsstempel

mål

beskrivelse

status

🧠 AI-drevet analyse

Genererer automatisk:

risikoanalyse

beskrivelse av hendelsen

tiltak

vurdering av mulig påvirkning

📊 Interaktivt dashboard

Frontend-appen viser:

aktive hendelser

historikk

systemer/assets

løste hendelser

AI-analyse

hendelseslogg

Alt oppdateres i sanntid når backend kjører.

🧩 Teknologistack
Backend

Python 3.x

FastAPI

SQLAlchemy

Pydantic

Uvicorn

SQLite

Frontend

React

Vite

Tailwind CSS

Axios

Zustand

Verktøy

Git & GitHub

Node.js & npm

Python venv

📦 Klone prosjektet
git clone https://github.com/ByAnnabel/CyberSense-Norge.git
cd CyberSense-Norge


Prosjektstruktur:

/backend   → FastAPI-server
/frontend  → React + Vite-klient

⚙️ Starte backend

Gå inn i backend-mappen:

cd backend


Opprett virtuelt miljø:

python3 -m venv venv
source venv/bin/activate


Installer avhengigheter:

pip install -r requirements.txt


Start backend-serveren:

python3 -m uvicorn app.main:app --reload


Backend tilgjengelig på:
👉 http://127.0.0.1:8000

👉 http://127.0.0.1:8000/docs

🖥️ Starte frontend

Gå til frontend-klienten:

cd ../frontend/cybersense-norge


Installer pakker:

npm install


Start utviklingsserver:

npm run dev


Frontend tilgjengelig på:
👉 http://localhost:3000

📁 Prosjektstruktur
CyberSense-Norge/
│── backend/
│   ├── app/
│   ├── venv/
│   ├── requirements.txt
│   └── main setup
│
│── frontend/
│   └── cybersense-norge/
│       ├── src/
│       ├── components/
│       ├── pages/
│       └── package.json
│
└── README.md

🧪 API-endepunkter
Metode	Endpoint	Beskrivelse
POST	/api/incidents/simulate?count=3	Simuler nye hendelser
GET	/api/incidents/active	Aktive hendelser
GET	/api/incidents/history	Historikk
POST	/api/incidents/{id}/resolve	Løs hendelse
GET	/api/incidents/{id}/advice	AI-analyse
POST	/api/assets	Opprett nytt asset
GET	/api/assets	Liste over assets
