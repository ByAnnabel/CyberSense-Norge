🛡️ CyberSense Norge

AI-drevet simulator for digitale krisehendelser i Norge

CyberSense Norge er et fullstack-system som simulerer cyberangrep, systemfeil og infrastrukturhendelser i sanntid. Prosjektet inkluderer backend (FastAPI) og frontend (React + Vite), og demonstrerer ferdigheter innen moderne webutvikling, API-design, real-time data, og AI-generert situasjonsanalyse.


🚀 Hovedfunksjoner
🔥 Cyberangrep-simulator
Simulerer realistiske hendelser som:
DDoS-angrep
Ransomware
Systemsvikt
Datainnbrudd
Desinformasjon

Hver hendelse får:
alvorlighetsgrad
tidsstempel
rammede systemer
geografisk lokasjon
generert beskrivelse

🧠 AI-drevet analyse (Gemini 2.0)
Automatisk generert:
Risikoanalyse
Tiltak og anbefalinger
Vurdering av spredningsfare
Tekstlig situasjonsforklaring

📊 Interaktivt dashboard
Frontend viser:
aktive hendelser
historikk
rammede systemer
kritikalitet
AI-generert rådgivning
live logs

🗂️ Teknologi brukt
Backend:
FastAPI
ByAnnabel / OpenAPI
Python 3.11
Uvicorn
Virtualenv

Frontend:
React
Vite
TailwindCSS
Axios
Zustand (state management)

📁 Mappestruktur
CyberSense-Norge/
│── backend/
│   ├── app/
│   ├── main.py
│   ├── requirements.txt
│   └── venv/
│
│── frontend/
│   └── cybersense-norge/
│       ├── src/
│       ├── components/
│       ├── pages/
│       └── package.json
│
└── README.md

⚙️ Installasjon & Oppstart
🔧 1. Start backend
cd backend
source venv/bin/activate
uvicorn app.main:app --reload


Backend kjører på:
👉 http://127.0.0.1:8000

Docs:
👉 http://127.0.0.1:8000/docs

🖥️ 2. Start frontend
cd frontend/cybersense-norge
npm install
npm run dev


Frontend kjører på:
👉 http://localhost:3000

🧪 API-endepunkter
Metode	Endpoint	Beskrivelse
POST	/api/incidents/simulate	Simuler nye hendelser
GET	/api/incidents/active	Aktive hendelser
GET	/api/incidents/history	Historikk
POST	/api/incidents/{id}/resolve	Løs hendelse
GET	/api/incidents/{id}/advice	AI-analyse
POST	/api/assets	Opprett nytt asset
GET	/api/assets	Liste over assets


📸 Skjermbilder
<img width="1275" height="702" alt="Skjermbilde 2025-11-30 kl  03 03 48" src="https://github.com/user-attachments/assets/a8ba9c1a-52af-41d5-88cf-c1f638c2c90a" />
<img width="315" height="709" alt="Skjermbilde 2025-11-30 kl  03 04 39" src="https://github.com/user-attachments/assets/307d911a-f12d-463b-9832-eb7d4f55bd1a" />
<img width="897" height="311" alt="Skjermbilde 2025-11-30 kl  03 05 14" src="https://github.com/user-attachments/assets/a78a40da-fda8-4d2c-bd43-7b89e3339248" />
<img width="903" height="357" alt="Skjermbilde 2025-11-30 kl  03 05 03" src="https://github.com/user-attachments/assets/bbd9bdc3-7e32-4d3a-ac87-a85bfcec79f3" />


📄 Lisens
MIT License

📬 Kontakt
ByAnnabel
Github: https://github.com/ByAnnabel
