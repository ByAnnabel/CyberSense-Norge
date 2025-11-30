🛡️ CyberSense Norge

AI-drevet simulator for digitale krisehendelser i Norge

CyberSense Norge er et fullstack-system som simulerer cyberangrep, systemfeil og infrastrukturhendelser i sanntid. Prosjektet inkluderer backend (FastAPI) og frontend (React + Vite), og demonstrerer ferdigheter innen moderne webutvikling, API-design, real-time data, og AI-generert situasjonsanalyse.

<img width="1323" height="718" alt="Skjermbilde 2025-11-30 kl  03 18 53" src="https://github.com/user-attachments/assets/73ac221f-02a8-4683-b848-790c5ca8140b" />

🚀 Hovedfunksjoner

🔥 Cyberangrep-simulator
* Simulerer realistiske hendelser som:
* DDoS-angrep
* Ransomware
* Systemsvikt
* Datainnbrudd
* Desinformasjon

Hver hendelse får:
alvorlighetsgrad
tidsstempel
rammede systemer
geografisk lokasjon
generert beskrivelse

<img width="1323" height="718" alt="Skjermbilde 2025-11-30 kl  03 21 33" src="https://github.com/user-attachments/assets/c0f6f470-f96b-4d59-b6ce-b20220654412" />


🧠 AI-drevet analyse (Gemini 2.0) / Automatisk generert:
* Risikoanalyse
* Tiltak og anbefalinger
* Vurdering av spredningsfare
* Tekstlig situasjonsforklaring

📊 Interaktivt dashboard
Frontend viser:
* Aktive hendelser
* Historikk
* Rammede systemer
* Kritikalitet
* AI-generert rådgivning
* Live logs

🗂️ Teknologi brukt
Backend:
* FastAPI
* ByAnnabel / OpenAPI
* Python 3.11
* Uvicorn
* Virtualenv

Frontend:
* React
* Vite
* TailwindCSS
* Axios
* Zustand (state management)

📁 Mappestruktur
* CyberSense-Norge/
* │── backend/
* │   ├── app/
* │   ├── main.py
* │   ├── requirements.txt
* │   └── venv/
* │
* │── frontend/
* │   └── cybersense-norge/
* │       ├── src/
* │       ├── components/
* │       ├── pages/
* │       └── package.json
* │
* └── README.md

⚙️ Installasjon & Oppstart
* 🔧 1. Start backend
* cd backend
* source venv/bin/activate
* uvicorn app.main:app --reload


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
* Metode	Endpoint	Beskrivelse
* POST	/api/incidents/simulate	Simuler nye hendelser
* GET	/api/incidents/active	Aktive hendelser
* GET	/api/incidents/history	Historikk
* POST	/api/incidents/{id}/resolve	Løs hendelse
* GET	/api/incidents/{id}/advice	AI-analyse
* POST	/api/assets	Opprett nytt asset
* GET	/api/assets	Liste over assets


📸 Skjermbilder


<img width="1323" height="718" alt="Skjermbilde 2025-11-30 kl  03 19 43" src="https://github.com/user-attachments/assets/667b68be-c2da-4576-9a72-c989ccc0bd4b" />


<img width="1323" height="718" alt="Skjermbilde 2025-11-30 kl  03 22 45" src="https://github.com/user-attachments/assets/d678d127-fcca-4797-88e4-bd77913d2087" />


📄 Lisens
MIT License

📬 Kontakt
ByAnnabel
Github: https://github.com/ByAnnabel
