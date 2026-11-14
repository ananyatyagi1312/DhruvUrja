# DhruvUrja ❄️
### Intelligent Energy Management for India's Polar Research Stations

DhruvUrja is an energy-management platform designed to support India's research stations in Antarctica. It brings together energy monitoring, predictive analytics, renewable-energy planning, and operational insights through a unified interactive dashboard.

The platform helps visualize station energy requirements, anticipate changing demand, and explore how different energy sources can be coordinated in challenging polar environments.

## ✨ What It Offers

- **Station Monitoring:** Interactive energy dashboards for Bharati, Maitri, and Himadri.
- **Demand Forecasting:** Weather-aware predictions to understand upcoming energy requirements.
- **Smart Energy Dispatch:** Optimization of solar, wind, battery storage, and diesel generation.
- **Scenario Simulation:** Explore alternative operating conditions and energy strategies.
- **Resupply Intelligence:** Assess fuel requirements, remaining reserves, and potential resupply risks.
- **Operational Recommendations:** Data-driven insights to support energy-management decisions.
- **Demo Mode:** Simulated station telemetry for exploring the platform locally.

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Python, FastAPI |
| Machine Learning & Analytics | NumPy, SciPy, scikit-learn |
| Runtime | Node.js |
| Database | SQLite |

## 🚀 Getting Started

### Prerequisites
- Python 3.14 (as specified by the project README; verify compatibility with your environment)
- Node.js and npm

### 1. Start the Backend

Open a terminal:

```bash
cd backend
python -m venv .venv
```

Activate the virtual environment and install dependencies.

**macOS / Linux**
```bash
source .venv/bin/activate
pip install -r requirements.txt
python run.py --demo-feed
```

**Windows**
```powershell
.venv\Scripts\activate
pip install -r requirements.txt
python run.py --demo-feed
```

### 2. Start the Frontend

Open another terminal:

```bash
cd frontend
npm install
npm start
```

### 3. Open the Dashboard

- **Application:** http://localhost:3002
- **API Documentation:** http://localhost:8001/docs

## 📁 Project Structure

```text
DhruvUrja/
├── backend/
│   ├── energy/
│   ├── main.py
│   ├── run.py
│   └── requirements.txt
├── frontend/
│   ├── public/
│   │   ├── assets/
│   │   ├── index.html
│   │   ├── app.js
│   │   └── styles.css
│   ├── package.json
│   └── server.mjs
├── .gitignore
├── README.md
└── vercel.json
```

## 🌍 Vision

Reliable energy is essential for scientific research in extreme environments. DhruvUrja explores how forecasting, intelligent energy allocation, and simulation can contribute to more informed energy-management decisions at remote polar research stations.

*Built as an energy-management prototype for extreme-environment research infrastructure.*

---

**Acknowledgements:** This repository is based on the collaborative DhruvUrja project. See the [original repository](https://github.com/harshit1330/DhruvUrja) for project history and contributor information.