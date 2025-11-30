🛡️ CyberSense Norge

AI-drevet simulator for digitale krisehendelser i Norge.

CyberSense Norge er et fullstack-prosjekt som simulerer cyberangrep, systemfeil og kritiske infrastrukturhendelser i sanntid. Dashbordet visualiserer aktive hendelser, rammede systemer, alvorlighetsgrad, tidslinjer og AI-generert analyse.

Prosjektet viser ferdigheter innen:

Backend/API-utvikling (FastAPI)

Frontend-utvikling (React + Vite)

Databasehåndtering (SQLAlchemy)

Systemdesign og real-time simulering

Full lokal utviklingspipeline

AI-analyse via integrert modell

🚀 Funksjoner
🔥 Cyberangrep-simulator

Simulerer hendelser som:

DDoS

Ransomware

Systemfeil

Desinformasjon

Hver hendelse kobles til et definert system/asset, med region og alvorlighet.

🧠 Innebygget AI-analyse

Genererer automatisk:

Situasjonsforståelse

Risikovurdering

Tiltaksforslag

📊 Dashbord i sanntid

Gir oversikt over:

Aktive hendelser

Historikk

Rammede systemer

Beskrivelser og status

Live hendelseslogg

⚙️ API-endepunkter

Klare og strukturerte routes som håndterer:

Assets

Hendelser

Simulering

Løsning av hendelser

AI-basert råd

🛠️ Teknologier

Backend:

Python

FastAPI

SQLAlchemy

Pydantic

Uvicorn

Frontend:

React

Vite

Tailwind CSS

Axios

💻 Lokal kjøring
1. Klon prosjektet:
git clone https://github.com/ByAnnabel/CyberSense-Norge.git
cd CyberSense-Norge

2. Start backend:
cd backend
source venv/bin/activate
uvicorn app.main:app --reload


Backend kjører på:
👉 http://127.0.0.1:8000

3. Start frontend:
cd ../frontend
npm install
npm run dev


Frontend kjører på:
👉 http://localhost:3000
